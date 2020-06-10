# Programming Assignment 2 : Lexical Scoping
### For the Coursera course [R Programming](https://www.coursera.org/learn/r-programming)


An example is developed for the application of the code 
`cachematrix.R`

Create a *square* matrix (because `solve` only handles square matrices)
Create the matrix during the call of makeCacheMatrix()


```
a <- makeCacheMatrix( matrix(c(3,4,13,14), nrow = 2, ncol = 2) )

summary(a)
     Length Class  Mode  
setMatrix    1      -none- function
getMatrix    1      -none- function
cacheInverse 1      -none- function
getInverse   1      -none- function


a$getMatrix()
  [,1] [,2]
[1,]    3   13
[2,]    4   14


cacheSolve(a)
     [,1] [,2]
[1,] -1.4  1.3
[2,]  0.4 -0.3
```
