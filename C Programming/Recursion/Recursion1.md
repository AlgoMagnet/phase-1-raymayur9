**Reference :** [Recursion 1](https://youtu.be/TZR6tMs4vmQ)
- When a function calls itself again, it is called recursion.
- This recursive call ( func() calling func(), which is calling func(), which is again calling func(), ans so on...) has an end or break point, which is called the base case.
- There are two parts of a recursive function - base condition and recursive condition.
- When a problem can be broken down to a sub-problem in a self similar fashion, then we can make use of recursion.
- Recursion is based on the idea of PMI (Principle of Mathematical Induction).
- Example - Print first n natural numbers (say, n = 5), using recursion. <br>
            Idea - f(n) = f(n-1) + print n [Base condition - return when n==0]
- Think - How can you print a sequence like this using recursion?<br>
          f(5) = 5 4 3 2 1 2 3 4 5
