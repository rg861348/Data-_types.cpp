Aim: To study and implement C++ Program Structure (Data Types).

Tool: VS Code

Theory: The program contains #include for input/output operations and then #include in order to show the string data type. using namespace std; enables the use of cout, cin, string, etc. without std::.

Program Flow In the main() method, the program demonstrates the declaration, input, and size of different C++ data types:

Integer (int): Input an integer from the user, print the integer along with its size in bytes using sizeof() which is of 4 bytes.

Floating-point (float): The program takes a float input (decimal number) and prints the value and its size in memory which is of 4 bytes.

Character (char): The program reads a character from input from the user, then prints it and its size which is of 1 bytes.

Double (double): A double-precision floating-point number is requested to be input by the user, then printed with its size which is of 8 bytes.

String (string): The program takes an input word (the program points out that cin will read an input until encountering the first space), displays the string, and its memory size. The program takes sizeof(string), which gives the string object's fixed size, not the string length which is of 24 bytes.

Boolean (bool): The program takes a boolean input(0=false, 1=true), displays it, then prints its size which is of 1 bytes.

Algorithm:
Step-wise Algorithm

Step 1: Start the program

Begin with including necessary headers: #include <iostream> and #include <string>.

Use using namespace std; to simplify code syntax.


Step 2: Declare an integer variable

1. Declare an integer variable a.


2. Prompt the user: Enter integer number.


3. Read input into a.


4. Display the value of a.


5. Display the memory size using sizeof(a).



Step 3: Declare a float variable

6. Declare a float variable b.


7. Prompt the user: Enter floating number.


8. Read input into b.


9. Display the value of b.


10. Display the memory size using sizeof(b).



Step 4: Declare a character variable

11. Declare a character variable c.


12. Prompt the user: Enter character.


13. Read input into c.


14. Display the value of c.


15. Display the memory size using sizeof(c).



Step 5: Declare a double variable

16. Declare a double variable e.


17. Prompt the user: Enter double number.


18. Read input into e.


19. Display the value of e.


20. Display the memory size using sizeof(e).



Step 6: Declare a string variable

21. Declare a string variable f.


22. Prompt the user: Enter string (no spaces).


23. Read input into f using cin.


24. Display the value of f.


25. Display the memory size using sizeof(f).



Step 7: Declare a boolean variable

26. Declare a boolean variable d.


27. Prompt the user: Enter boolean value (0 or 1).


28. Read input into d.


29. Display the value of d.


30. Display the memory size using sizeof(d).


Step 8: End the program

31. Print a message indicating the end of program.


32. Use return 0; to exit successfully.




Conclusion: The program display all the values and their sizes in memory. This makes it easier for users to learn how to apply datatypes practically in C++, but also introduces them to the concept of memory allocation of datatypes.
