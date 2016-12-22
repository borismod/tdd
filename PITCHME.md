TDD

#HSLIDE
TDD in a nutshell

1. Write a failing test
2. Write minimum amount of code to satisfy it
3. Refactor

#HSLIDE

##Writing the test

Focus on the behaviour and treat the code as black box
Feed it with input and verify its output

#HSLIDE

##Writing the code

Write only the code that satisfies the test
Do not write code for future use
Do not optimize

#HSLIDE

##Refactoring

Modify the code to be cleaner and make sure that tests still pass  

#HSLIDE

Kata

#HSLIDE

## Calculator Kata

1. An empty string returns zero
2. A single number returns the value
3. Two numbers, comma delimited, returns the sum
4. Two numbers, newline delimited, returns the sum
5. Three numbers, delimited either way, returns the sum
6. Negative numbers throw an exception
7. Numbers greater than 1000 are ignored

#HSLIDE
## Advanced 
8. A single char delimiter can be defined on the first line (e.g. //# for a ‘#’ as the delimiter)
9. A multi char delimiter can be defined on the first line (e.g. //[###] for ‘###’ as the delimiter)
10. Many single or multi-char delimiters can be defined (each wrapped in square brackets)