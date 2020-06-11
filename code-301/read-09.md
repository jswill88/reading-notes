# Functional Programming

## Concepts of Functional Programming
* A function is pure if it always gives the same results given the same arguments and it does not have any side effects
* Everything used in the function will be passed to the function so no external objects change
* Functions that read files or generate random numbers are not pure
* You should not modify global variables with functional programming
* This makes the code easier to test
* Recursion helps keep variables immutable
* It is good to minimize the number of for loops used

## Refactoring JavaScript for Readability
* Good code is in the middle ground between speed and maintainability
* One strategy is to return early from functions
* Use web APIs when possible
* It is important to code well the first time, because companies may not be convinced to spend money to refactor
