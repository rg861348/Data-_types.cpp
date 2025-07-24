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

Start the program. Declare an integer variable a. Prompt: Enter integer number Input: Read value into a Output: Display value of a and its size using sizeof(a) Declare a float variable b. Prompt: Enter floating number Input: Read value into b Output: Display value of b and its size using sizeof(b) Declare a character variable c. Prompt: Enter Character Input: Read value into c Output: Display value of c and its size using sizeof(c) Declare a double variable e. Prompt: Enter double int number Input: Read value into e Output: Display value of e and its size using sizeof(e) Declare a string variable f. Prompt: Enter String Input: Read value into f Output: Display value of f and its size using sizeof(f) Declare a boolean variable d. Prompt: Enter Boolean value Input: Read value into Output: Display value of d and its size using sizeof(d) End the program.

Conclusion: The program display all the values and their sizes in memory. This makes it easier for users to learn how to apply datatypes practically in C++, but also introduces them to the concept of memory allocation of datatypes.
