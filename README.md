1. Define matrix mymat by replicating the sequence 1:5 for 4 times and transforming into a matrix, sum
over rows and columns.

Ans. mymat<-matrix(rep(1:5,4),byrow = FALSE,nrow = 5)
mymat
colSums(mymat)
rowSums(mymat)
