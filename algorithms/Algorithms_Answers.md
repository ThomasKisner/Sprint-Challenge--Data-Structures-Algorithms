Add your answers to the Algorithms exercises here.

A.
n = 2 
a=0
2*2*2 = 8
a = 0 + 4

a = 4
a = 4+4
A is no longer less than n*n*n
Because this ran the same number of times as the input N I believe it is o(n). The n*n in the bottom cancels out the two above it in the while statement. It could be rewritten as while a < n = a = a * n

b. I believe this falls somewhere between 0(2^n) and o(n^2). I plugged this into a replit and the results are bigger than n^2, but smaller than 2^n

c. I think this is is a constant. No matter what n equals either a 0 i being returned or the result of the return statement. The number of operations never grows regardles of how large n grows.

Exercise Two: 
    I think the way to do this would be to bisect the building, and then bisect the bisections. If the egg doesn't break from the middle go halfway up. If it breaks there go halfway down to the middle and try again. Rinse and repeat until you find the final floor it will break on. I believe this is a log n approach to solving this problem, and should save a lot of eggs.