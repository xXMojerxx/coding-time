# LIST AND INDEX ;-;
> im sorry if this isnt sufficient information, still starting to learn and also dont really know how
> to make actual good tutorials :P

List are created similar to variables, you have to indicate the variable type and call the variable name. The only expection to creating a list in c++ is indicating the amount of items inside the list as well as having the
items in the list around brackets (Its not allways applicable to add an indicator for the amount of items in a list):
```cpp
variableType variableName [amount-of-items] = { 
  item1, 
  item2, 
  item3,
};
```
Here is the base list that we are going to base this section off of:
```cpp
char letters[4] = {
  'a',
  'b',
  'c',
  'd'
};
```
## LENGTH OF A LIST
To find the lenght of a list, you can either look at the amount of items indicated by the list or you can use special code to figure it out. For example, if i wanted to find the lenth of a list, i would use:
```cpp
printf("%d", sizeof(listName)/sizeof(int));
/* OR YOU CAN USE IF LAZY :) */
cout << sizeof(listName)/sizeof(int);
```
Using the base list, I can use the code:
```cpp
cout << sizeof(letters)/sizeof(int);//This should output the value of 4 since there are 4 items in the list
```
## MULTIDIMENSIONAL LISTS
In c++, you can create multidimesional lists. Multidimesional lists are created by having 2 indicators of the amount of items. So if you wanted to create a list that was a 4 X 4 area, it would be:
```cpp
char letters[4][4] = {
  {'a', 'b', 'c', 'd'};
  {'e', 'f', 'g', 'h'};
  {'i', 'j', 'k', 'l'};
  {'m', 'n', 'o', 'p'};
};
cout << letters[1][1]
```
