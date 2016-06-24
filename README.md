# finding-points-on-curve-over-finite-field

For a finite field F, a function f, and a number a. The function 


soln4 returns an array of the points (x,y,z,w) such that f(x,y,z,w) = a 

example: 

in Sage

def f2(x,y):

  return x^2 + y^2

  soln4(GF(3), 1, f2)

->(0,1)

  (0,2)

  (1,0)

  (2,0)
  
