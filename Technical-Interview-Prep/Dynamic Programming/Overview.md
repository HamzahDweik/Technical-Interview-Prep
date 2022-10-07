Strategies
[[Bottom-Up]]
[[Top-Down]]
[[Goal Post Mover]]

A few examples of these problems include:
- Fibonacci
	-> Top down approach: Fib(n-1) + Fib(n -2)
	-> Bottom up approach: List = [1, 1]
		List(n) = List(n-1) + List(n-2). This builds your list up and eliminates duplication in steps.

- Pascals Triangle (n choose k)
	-> Top down approach: (n-1 choose k) + (n-1 choose k-1)
	-> Bottom up approach: Use an n x k matrix
		Matrix\[n]\[k] = Matrix\[n-1]\[k] + Matrix\[n-1]\[k-1]



