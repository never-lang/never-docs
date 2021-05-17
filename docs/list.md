---
title: Singly Linked List
---

# Singly Linked List


```never
enum List { Empty, Node { value : int; tail : List; } }
```

```never
func list_add(list : List, value : int) -> List
{
    var l = List::Empty;
    l = list;
    List::Node(value, l)
}
```

```never
func list_print(list : List) -> int
{
    var node = List::Empty;

    node = list;
    while (node != List::Empty)
    {
        if let (List::Node(value, tail) = node)
        {
            prints(value + "\n");
            node = tail
        }
        else
        {
            node = List::Empty
        }
    }
}
```

```never
func list_print_rec(list : List) -> int
{
    if let (List::Node(value, tail) = list)
    {
        prints(value + "\n");
        list_print_rec(tail)
    }
    else
    {
        0
    }
}
```

```never
func list_print_rec_2(list : List) -> int
{
    match (list)
    {
        List::Empty -> 0;
        List::Node(value, tail) -> { prints(value + "\n"); list_print_rec_2(tail) };
    }
}
```

```never
func main() -> int
{
    var list_rec = List::Node(10, List::Node(20, List::Node(30, List::Node(40, List::Empty))));

    list_print_rec(list_rec);
    list_print_rec_2(list_rec);

    var list = List::Empty;
    list = list_add(list, 40);
    list = list_add(list, 30);
    list = list_add(list, 20);
    list = list_add(list, 10);

    list_print(list);

    0
}
```

