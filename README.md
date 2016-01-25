# Assignment2
#Output 
> source("C:/Users/yttik/Dropbox/Coursera/RPrograming/assessment3.R")
> a <- makeCacheMatrix();
> summary(a);
           Length Class  Mode    
set        1      -none- function
get        1      -none- function
setinverse 1      -none- function
getinverse 1      -none- function
> a$set( matrix(c(1,2,12,13), nrow = 2, ncol = 2) );
> a$get();
     [,1] [,2]
[1,]    1   12
[2,]    2   13
> cacheSolve(a)
Error in cacheSolve(a) : '...' used in an incorrect context
> cacheSolve(a)
Error in cacheSolve(a) : '...' used in an incorrect context
> source("C:/Users/yttik/Dropbox/Coursera/RPrograming/assessment3.R")
> a <- makeCacheMatrix();
> summary(a);
           Length Class  Mode    
set        1      -none- function
get        1      -none- function
setinverse 1      -none- function
getinverse 1      -none- function
> a$set( matrix(c(1,2,12,13), nrow = 2, ncol = 2) );
> a$get();
     [,1] [,2]
[1,]    1   12
[2,]    2   13
> cacheSolve(a)
           [,1]        [,2]
[1,] -1.1818182  1.09090909
[2,]  0.1818182 -0.09090909
> cacheSolve(a)
getting cached data
           [,1]        [,2]
[1,] -1.1818182  1.09090909
[2,]  0.1818182 -0.09090909
