# LOOPS ^w^
Loops executes lines of codes until the specific conditions are met. Loops are important in almost all programs due to reducing the amount of lines of code used, reduces the amount of errors, and makes it more readable. Some most common instances of loops in code would be:
## FOR LOOPS
### ``` FOR LOOPS ```
For loops are used to identify specificaly how many times you want the loop to itterate. Used mostly for itteration though a list. An examle of a for loop would be:
```cpp
for (int i = 1; i <= 3; i++){
  cout << i << "\n"; /* Executes 3 times */
}
```
### ``` NESTED FOR LOOPS ```
Nested for loops are basically two for-loops inside of each other. Nested for-loops are most commonly used to get specific locations in multidimensional list, where the "inner loop" would itterate once per "outter loop". An example of a nested for loop would be:
```cpp
// The outer loop
for (int i = 1; i <= 5; i++){
  cout << "Outer :" << i << "\n"; /* Executes 5 times */
  
  //The inner loop
  for (int index = 10; index >= 5; i--){
    cout << "Inner :" << index << "\n"; /* Executes 25 times (5 * 5) */
  }
}
```
### ``` FOREACH LOOPS ```
Foreach loops are a more simpler way to itterate through all indexes inside a list. An example of a foreach loops would be:
```cpp
string friendsUserNames [5] = {"BlueAce", "smemer", "NoLongerPadoru", "dyson", "enscribe"};
for (int i : friendsUserName) {
  cout << "My friends username :) :" << i << "\n"; /* outputs all the names inside the list */
}
```
## WHILE LOOPS
### ``` WHILE LOOPS ```
While loops is the most simplified loop. A while loop loops through a block of code aslong as the condition met is true. An example of a while loop would be:
```cpp
int i = 10;
while (i >= 1){ /* Executes throught the code segment 9 times */
  cout << i << "\n";
  i--;
}
```
### ``` DO/WHILE LOOPS ```
Do/while loops itterate throught the block of code at least once, and will keep on itterating as long as the condition is being met (checking if the condition is true). An example of a do/while loop would be:
```cpp
int i = 0;
do { /* Executes once before checking the while loop condition */
  cout << i << "\n";
  i++;
}
while (i < 5); /* If condition is met, executes until condition returns as false */
```
