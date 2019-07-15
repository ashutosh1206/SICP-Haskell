## Intro to lists

1. Data structures containing the same type of data --> homogenous data structures. Data structures containing different types of data --> heterogenous data structures. Haskell lists are homogenous.   
   ```haskell
        Prelude> let list1 = [1, 2, 3, 4]
        Prelude> let list1 = [1, 'a', 3, 4]
        <interactive>:3:14:
        No instance for (Num Char) arising from the literal ‘1’
        In the expression: 1
        In the expression: [1, 'a', 3, 4]
        In an equation for 'list1': list1 = [1, 'a', 3, ....]
   ```
2. Answer:
   ```
   let list1 = [1, 2, 3, 4]
   ```
3. Element can be added to a list using `++` and `:` operators.
```
[1, 2, 3, 4] ++ [5]
[1, 2, 3, 4] ++ [5, 6, 7, 8]
1:[1, 2, 3, 4]
```
   + Answer 3a
     + While `++` operator can combine lists at both ends, `:` can only prepend one element to a list.
     + Both the arguments of `++` operator should be enclosed in `[]`, while this is not case with `:`.  

   + Answer 3b:
     + `++` operator traverses the first argument list and then appends the second argument to it. In situations where the first argument is too large, it will take time to append elements to the list. `:` is much faster, as it prepends elements almost instantaneously.

4. Elements are indexed in a list using `!!` operator.
```
[1, 2, 3, 4] !! 3
```

5. 
