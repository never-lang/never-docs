---
title: Filter Map Reduce
---

This example shows how to create filter, map and reduce functions which
operate on a record.

```never
record tab
{
    t[T] : int;
}

func filter(t : tab, f(e : int) -> bool) -> tab
{
    tab( [ e | e in t.t; f(e) == true ] : int )
}

func map(t : tab, f(e : int) -> int) -> tab
{
    tab( [ f(e) | e in t.t ] : int )
}

func reduce(t : tab, i : int, f(a : int, e : int) -> int) -> int
{
    let a = i;
    let j = 0;

    for (j = 0; j < t.T; j = j + 1)
    {
        a = f(a, t.t[j])
    };

    a
}

func print_tab(t : tab) -> int
{
    let i = 0;

    for (i = 0; i < t.T; i = i + 1)
    {
        print(t.t[i])
    };

    0
}

func main() -> int
{
    let t = tab( [1, 2, 3, 4, 5, 6, 7, 8] : int );

    prints("---tab---\n");
    print_tab(t);

    prints("---filter---\n");
    print_tab( filter(t, let func(e : int) -> bool { (e % 2) == 0 }) );

    prints("---map---\n");
    print_tab( map(t, let func(e : int) -> int { 10 * e }) );

    prints("---reduce---\n");
    print( reduce(t, 0, let func(a : int, e : int) -> int { a + e }) );

    prints("---filter.map.reduce----\n");
    print(reduce(map(filter(t,
                            let func(e : int) -> bool { (e % 2) == 0 }),
                     let func(e : int) -> int { 10 * e }),
                 0,
                 let func(a : int, e : int) -> int { a + e })
         );
    0
}
```
