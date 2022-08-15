# matrix-chain-multiplication
Using dynamic programming to find the most optimal way to multiply n matrices

Example:

Lets us multiplay 3 matrices a, b and c
with the following orders
a(5x20) b(20x10) c(10x50)

we can multiply this in two ways

1. a(bc)
2. (ab)c

the frist one takes 20x10x50 + 5x20x50 = 15000 operations
where as the second one takes 5x20x10 + 5x10x50 = 3500 operations 

as you can clearly see going with the second option is more efficient.
