# STARTING IN C++ O.o
To start coding in c++, there are multiple ways to start off. First, you need a dedicated software witht he correct setup to 
start coding (in which idk which softwares are good :P). But, once youhave your dedicated software, it looks like:
```cpp
#include <iostream>
using namespace std;

int main() {

  //This is where you are going to be inputing all of you code in
  
  return 0;
}
```


This is going to be your basic format for c++. As you go along learning and making your own things, this starting point might become more and more complex due to the "add-ons" you have to put in.
There are 4 main things to 'memorize' when creating a c++ file (you dont really need to, but its helpful):
```cpp
#include <INSERT HERE> //This is the "add-ons" to input more commands to use when coding (called directives)
using namespace std //Used to organize code as well as preventing name collisions
int main(){ INPUT CODE HERE } //Begining fuction for c++, basically the main function where you input you code
return 0; //ends the function at hand, 
```
To have a better c++ experience, here are some "add-ons" that are very usefull and more practical when coding (when comming from Code.org):
```cpp
#include <iostream> /* Your beginning directive that is given to you */
#include <stdio.h> /* Adds printf, scanf, puts, and NULL to your program, better for output to console and user control */
#include <stdlib.h> /* Adds srand as well as rand, which is used for random number generation */
#include <time.h> /* Adds time, useful when creating random number generation (for some reason?) and timed-based events */
```
