#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

> a) 
>
>Answer: O(n) Linear
>
> This is a linear function that first checks if the condition: is 'a' less than n³? 
>   • if 'a' is greater than the result of n³ the loop will not be executed.
>   • if 'a' is less than the result n³ the loop executes, and while 'a' is less than
>     n³ it sets 'a' = to the value of n² + 1, then it stops when 'a' is greater than n.
>
> As the size of n increases, the number of operations increase proportionally which is linear time.


> b) 
>
>Answer: O(n log n) Linearithmic

>  
>The number of iterations required to satisfy the condition that stops the while loop 
> increases in relation to the size of n. It is limited by the size of n and 
> increases in size slightly over time, therefore it is Linearithmic.

> c) 
>
>Answer: O(n) Linear
>
> This is a linear function which takes in n and performs a single operation on the value of n. 
>Although a recursive call is made, the number of operations increase proportionally according
> to the size of n, which is linear time.



## Exercise II

> Suppose that you have an n-story building and plenty of eggs. Suppose also that an egg gets broken if it is thrown off floor f or higher, and doesn't get broken if dropped off a floor less than floor f. Devise a strategy to determine the value of f such that the number of dropped + broken eggs is minimized.

> Write out your proposed algorithm in plain English or pseudocode AND give the runtime complexity of your solution.


> Answer: I would use dynamic programming for this problem, with a goal of O(n * 1)
>
> First, identify the base cases for the outcome of a single egg drop:
>   Base case #1: egg does not break
>   Base case #2: egg does break
>
>  Next simulate those base cases on all the possible sub-problems to find the ( constant time )
>   • special case of 1 a 0 or 1 floor building ( linear is best case time )
>   • best case (lower bound)
>   • worst case (upper bound)
> 
>   tHEN save the results of these simulations in a table.
>
>  This approach makes it possible to refference the table according to the number of floors
