# CONDITIONALS :)
Conditionals (Also known as conditional statements) are used to check and compare two different opperators. If the statement returns as true, that means it would run the code function. If the statement returns as false, it would skip the code segment and continute to run as normal.
Some common statements that are well known are:

### ```IF STATEMENTS```

If statements are most commonly used when coding. Checks if the condition returns as true, and if false, skips the code segment

### ```ELSE-IF STATEMENTS```

Else-if checks are similar to if statemments but instead of skipping the code segment, it runs a different code segment if returns as false

```cpp
int number1 = 5;
int number2 = 10;

if (number1 == number2){ /* if statements gets checked, continues on if false */

  cout << "the first number is equal to the second number"; // Returns this value if condition is met
  
} else if (number1 < number2){ /* else-if statement gets checked if the if statement is false */

  cout << "number 2 is greater than number 1"; // Returns this value if condition is met
  
} else { /* else statement gets checked if either statements returns as false */

  cout << "number 1 is greater than number 2"; // Returns this value if condition is met
  
}
```
