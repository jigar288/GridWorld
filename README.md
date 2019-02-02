# GridWorld

***code is protected and can be provided for valid reasons***

C++ project called Grid World keeps track of world’s information. For this project, I was able to improve from a slower quadratic read/write runtime to a much faster constant runtime by using combination of data structures (queues, doubly linked lists, multidimensional dynamic arrays, and vectors). Source code is protected and can be provided if requested for valid reasons.


## Running Program:

1) Clone/Download this repo. Open any linux terminal
2) Browse to directory with the "a.out" file 
3) use ./a.out command to execute run program

## Program Operations:

All O(1) constant time operations:

- birth() : creates a new person & places that person in district (row, col) 

- death() : if alive, person is removed from its current district and the entire world

- move(): if given person is alive, and specified target-row and column are valid, person is moved to specified district

- population(): simply returns the total number of (living) people in the entire world/grid

- population(int row, int col): simply returns the total number of (living) people in district specified by (row,col)

- whereis(): if personID represents a currently living person, the row and column where that person currently lives is reported 


