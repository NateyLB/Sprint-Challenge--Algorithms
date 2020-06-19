#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a)
O(3n - a)


b)
O(n^2)


c)
O(n)
or bunnies

## Exercise II
Suppose that you have an n-story building and plenty of eggs. Suppose also that an egg gets broken if it is thrown off floor f or higher, and doesn't get broken if dropped off a floor less than floor f. Devise a strategy to determine the value of f such that the number of dropped + broken eggs is minimized.

Write out your proposed algorithm in plain English or pseudocode AND give the runtime complexity of your solution.

lets use some sort of binary search

if the middle does break and middle+1 does break, return middle

if does break, recuresively call on the start to middle -1

O(log n)



