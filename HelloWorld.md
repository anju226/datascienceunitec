## This is a markdown file

1. https://github.com/anju226/datascienceunitec/tree/master
2. https://github.com/anju226/datasharing
3. table
4. character
5. a matrix with 2 columns and 3 rows 
cbind(x, y)
     x  y
[1,] 1  3
[2,] 3  2
[3,] 5 10

6. 
d) a character vector of length 1.  
e) a character vector containing the letter "a". 

7. an numeric vector with the values 3, 5, 5, 7. 
8. x[x < 6] <- 0

9. 
   #converting into a dataframe
matr<- as.data.frame.matrix(datalines)

#extracting first two rows and all columns of a dataframe
z<- matr[1:2,]

   Ozone Solar.R Wind Temp Month Day
1    41     190  7.4   67     5   1
2    36     118  8.0   72     5   2

10. c) 153

11. d) 21
oz47<- matr[47,1]

12. a) 37
sum(is.na(datalines$Ozone))

13. a) 42.1
mean(datalines$Ozone, na.rm = TRUE)  

14. b) 115
#extracts all the columns where month is equal to 5
month5 <- subset(datalines, Month == 5)
month5
month5[which.max(month5$Ozone),]

15. b) The number 27 is returned
> cube(3)
[1] 27

16. d) 'x' is a vector of length 10 and 'if' can only test a single logical statement.
Warning message:
In if (x > 5) { :
  the condition has length > 1 and only the first element will be used

17. a) 10
f <- function(x) {
  g <- function(y) {
    y + z
  }
  z <- 4
  x + g(x)
}

z <- 10
f(3)

18. b) 10

19. 


