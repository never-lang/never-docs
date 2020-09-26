---
title: Filter Map Reduce
---

This example shows how to create filter, map and reduce functions which
operate on a record.

First a record which contains table with arbitraty size.

```never
record tab
{
    t[T] : int;
}
```

Then lets define filter, map and reduce functions. Filter and map
functions use list comprehension to construct new tables. Filter
uses ```f``` function to get all elemenst which satisfy condition.
Map function creates new record with table where all elements
are mapped to value of ```f``` function.

```never
func filter(t : tab, f(e : int) -> bool) -> tab
{
    tab( [ e | e in t.t; f(e) == true ] : int )
}

func map(t : tab, f(e : int) -> int) -> tab
{
    tab( [ f(e) | e in t.t ] : int )
}
```

Reduce function lets to execute ```f``` function over all elements
of the record. Initial value is set with ```i``` parameter. First
parameter ```a``` serves as an accumulator which holds current value.
Second parameter ```e``` contains current table element. As result
single integer value is obtained. In this example addition is used.
When passing multiplication, then initialal value should be set to 1.
Otherwise value 0 would be returned.

```never
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
```

Last lets define an auxiliary function to print the record.
Please note how array size is obtained to iterate over all elements of the array.

```never
func print_tab(t : tab) -> int
{
    let i = 0;

    for (i = 0; i < t.T; i = i + 1)
    {
        print(t.t[i])
    };

    0
}
```

And now all functions combined to demonstrate how they work.

```never
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

Thanks!

