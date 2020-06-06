---
title: FFI Demo
---

# Foreign Function Interface - Code Snippet

```C
#include "nev.h"
#include "fficall.h"
#include <stdio.h>
#include <assert.h>

void test_zero()
{
    assert(test_char('A') == 'B');
    assert(test_char('B') == 'C');
    assert(test_char('Z') == 'A');
}

void test_one()
{
    ffi_decl * fd = ffi_decl_new(20);
    
    ffi_decl_delete(fd);
}

int pos_x = 0;
int pos_y = 0;

int turn_left()
{
    printf("turn_left\n");
    return 0;
}

int turn_right()
{
    printf("turn_right\n");
    return 0;
}

int go_ahead(int dist)
{
    printf("go_ahead %d\n", dist);
    
    pos_x += dist;
    pos_y += dist;
    
    return dist;
}

int get_x() { return pos_x; }
int get_y() { return pos_y; }

int fire(int at_x, int at_y)
{
    printf("FIRE! @ (%d, %d)\n", at_x, at_y);
    return 0;
}

int program_one(program * prog)
{
    const char * prog_str =
        "var cnt = 0;"
        " "
        "extern \"host\" func turn_left() -> int "
        "extern \"host\" func turn_right() -> int "
        "extern \"host\" func go_ahead(dist : int) -> int "
        "extern \"host\" func get_x() -> int "
        "extern \"host\" func get_y() -> int "
        "extern \"host\" func fire(at_x : int, at_y : int) -> int "
        " "
        "func on_click() -> int"
        "{ "
        "  cnt = cnt + 1; "
        "  print(cnt); "
        "  0 "
        "} "
        " "
        "func on_key(dist : int) -> int "
        "{ "
        "   turn_left(); "
        "   go_ahead(dist); "
        "  "
        "   fire(get_x() + 20, get_y() + 30); "
        "  "
        "   0 "
        "}";
    
    return nev_compile_str(prog_str, prog);
}

int execute_prog(program * prog, int param1)
{
    int i = 0;
    int ret = 0;
    object result = { 0 };

    vm * machine = vm_new(DEFAULT_VM_MEM_SIZE, DEFAULT_VM_STACK_SIZE);

    ret = nev_prepare(prog, "on_key");
    if (ret == 0)
    {
        prog->params[0].int_value = param1;

        ret = nev_execute(prog, machine, &result);
        if (ret == 0)
        {
            assert(result.type == OBJECT_INT && result.int_value == 0);
        }
    }

    for (i = 0; i < 10; i++)
    {
        ret = nev_prepare(prog, "on_click");
        if (ret == 0)
        {
            ret = nev_execute(prog, machine, &result);
            if (ret == 0)
            {
                assert(result.type == OBJECT_INT && result.int_value == 0);
            }
        }
    }

    vm_delete(machine);

    return 0;
}

void test_two()
{
    program * prog_one = program_new();

    int ret1 = program_one(prog_one);
    if (ret1 == 0)
    {
        execute_prog(prog_one, 60);
    }

    program_delete(prog_one);
}

int main(int argc, char * argv[])
{
    test_zero();
    test_one();
    test_two();
    
    return 0;
}
```

