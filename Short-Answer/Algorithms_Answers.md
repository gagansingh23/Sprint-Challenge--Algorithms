#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) A is O(n) because it is linearly dependant on the input size, as n is increased the iterations follow. 


b) the outer for loop is O(n) because it takes the n amount of iterations, however the inner loop is O(log(n)) because j is *=2 which makes it reach longer. 


c) it is O(n) because it a recursive call on bunnies until it = 0. 

## Exercise II

Using the binary search tree, I would first start at middle, if egg breaks the current floor will be -1, but if the egg doesnt break the current floor will be plus 1, until the egg breaks. So depending on the middle we would either keep moving up or down(left or right) until it breaks.

In  addition,  
0 to low floor and f for high floor, set mid floor / 2 of high floor, if egg breaks at midfloor, set high floor to mid, oppositely if egg doesnt break set mid floor to low. The runtime which will be O(log(n)). 


