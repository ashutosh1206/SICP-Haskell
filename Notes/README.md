Read "So what's Haskell" section

Strings are a list of characters in haskell. Hence, all the functions that are applicable on lists are applicable on strings too!

1. Give examples for performing simple arithmetic operations in haskell
   + Illustrate whether or not you can use multiple arithmetic operators in a single line
   + Illustrate how to multiply a positive number with a negative number
   + What happens when we try to do arithmetic operations on two values of different data types?
   + Can `+` operator work for values other than integers?
2. Give examples for performing boolean algebra in haskell
3. Give an example for testing equality and inequality of values in haskell
   + What happens when values of two different data types are checked for equality?
4. What are infix and prefix functions? Give an example for each.
   + What is the syntax for calling any function with a parameter in haskell?
5. Give an example of how to call functions with their parameters in haskell.
   + What is the difference in the syntax between function calls in haskell and other imperative languages?
6. Inbuilt functions
   + succ
   + min
   + max
   + mod
7. If there is a prefix function having two parameters, explain with the help of an example how haskell allows the ability to make the function infix.
8. Give an example of nested function calls in haskell

## Intro to Functions
1. What is the syntax for declaring a function in haskell? Explain with the help of a function that triples a number.
2. Can you call other functions from within a function? Illustrate.
   + What is the benefit of this technique?
   + Explain how the order of declaration of caller and calling function matters in haskell
3. Give an example of conditional statements put inside a function
4. What is the difference between if statements in imperative languages and haskell?
   + Explain why is the difference there.
5. Can we add apostrophe in variable names in haskell? What is it usually used for?
6. Can we start a function's name with a capital letter in haskell?

## Intro to Lists
1. What are homogenous and heterogenous data structures? Are haskell lists homogenous or heterogenous? Justify with the help of an example
2. Give an example of declaring a list in haskell
3. Explain different ways to add element to a list in haskell
   + What is the difference between using `++` and `:` operator?
   + Which one of the two functions is faster and why?
4. How do we index elements in a list?
5. Explain some features of nested list
   + Length of lists in a nested list
   + Type of lists in a nested list
6. Give an example of list comparison in haskell
   + How are lists actually compared?
7. Explain with the help of an example, the working of following functions on lists in haskell:
   + head
   + tail
   + init
   + last
   + length
   + null
   + reverse
   + take
     + What happens when we try to take 0 elements from the list?
     + What happens when we try to take more elements than there are in the list?
   + drop
     + What happens when we try to drop 0 elements from the list?
     + What happens when we try to drop more elements than there are in the list?
   + maximum
   + minimum
   + sum
   + product
   + elem
8. **Texas ranges**: Give an example of a simple texas range on integers and characters each
9. Give an example of how texas ranges can be used to generate a list of elements spaced by a fixed value
10. Give an example of how texas ranges can be used to print values in decreasing order
11. Can we use floating point numbers in texas ranges? If so, how?
12. Explain how you can slice `x` elements from an infinite length texas range
13. Explain following functions:
    + cycle
    + repeat
    + replicate
14. **List Comprehension**: What are the various components of a list comprehension?
15. Write a list comprehension to print 10 even numbers starting from 10 and that is divisible by 4
16. Write a list comprehension that calculates the length of a list

## Tuples
1. What are the differences between tuples and lists?
2. 
