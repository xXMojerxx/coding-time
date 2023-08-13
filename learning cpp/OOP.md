# OOP (CLASSES / OBJECTS) -.-
> im sorry if this isnt sufficient information, still starting to learn and also dont really know how
> to make actual good tutorials :P

To first clear things up, OOP is also known as Object Oriented Programming. Objects created from OOP contrain data as well as functions that are ment to be performed. The reason to why OPP is important for C++ is because it provides a way to use these objects to model real world problems. OPP contains two different aspects:

### ``` CLASSES ``` 
Classes are a template that are ment to hold objects within. Classes are usualy indicated by broader terms such as fruits, cars, bags, etc.
### ``` OBJECTS ```
Objects are more specific terms that tells the specifics of whats within the class. They are mostly indicated by specifics terms such as Apple/Bannana, Toyota/Mercedes, Jansport/Calvin Klein, etc.

## To create a class:
```cpp
class theClass { /* This creates the class with the indicated name */

  public: /* This specifies what the access is going to be */

    int myNum; /* This creates the variable that is going to be used within the class */
    string myString; /* This also creates another variable that is going to be used within the class*/

    void showData() {
      /* Output the values of the objects as well as the variables */
      cout << "First object value:" << myNum << endl;
      cout << "Second object value:" << myString;
    }
};
```
## To create an object:
```cpp
/* using the same class that was just created... */

int main(){
  theClass myObj; /* This creates the object within the class */

  /* These change the atributes/values to the class variables  using the object */
  myObj.myNum = 20; 
  myObj.myString = "Hello World";

  myObj.showData();

  return 0;
}
```
^OUTPUT ^
```
First object value: 20
Second object value: Hello World
```
