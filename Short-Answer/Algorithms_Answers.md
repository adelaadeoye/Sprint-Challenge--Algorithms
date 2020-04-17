#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n)
This is because the while loop method run n-times and there is a constant increment to a 


b) O(n^2) This is because it is a nested loop and a such increases the loop variable twice  


c)O(n^2) At first call of the bunnyEars func it is O(n) then the recursive call at line 29 makes a loop form the we have O(n^2) but progressively if the base case is not reached then we have O(n^2 +1) and so on but the additions is insignificant to the value of n^2 so the time complexity is O(n^2)

## Exercise II

Pseudocode 

1. Accept the number of floor in the story building and the create an array same size with the story building

2. Create function to move up and down the building 

3. Create a function  call throw, this function will have some extra logic that determine whether to break an  egg base on the current position of the person

There will be a global variables current_position and former_position which is accessible and updatable by  other functions. 


The time complexity is O(n^2) as the pseudocode can be implemented recursively or iteratively. 

also there could be replan for a optimal solution