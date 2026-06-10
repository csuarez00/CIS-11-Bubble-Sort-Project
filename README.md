CIS-11 Bubble Sort Sorcerers (LC-3 Assembly)
A Bubble Sort Algorithm built using LC-3 Assembly language that accepts 8 integers inputted by the user, sorting them in ascending order, and displaying sorted results. 
Live Demo
Program is run using LC-3 Simulator.
________________________________________
<a id="table-of-contents"></a>
## Table of Contents </br>
•	General Information</br>
•	Technologies Used
•	Features
•	Screenshots
•	Setup
•	Usage
•	Project Status
•	Room for Improvement
•	Acknowledgements
•	Contact
________________________________________
General Information
This project was developed for CIS 11 as a team assignment focused on implementing Bubble Sort in LC-3 Assembly Language.
Problem Solved
Efficiently sorting data is a common requirement. This helps to demonstrate how a sorting algorithm can be implemented in assembly.
Purpose
•	Practice LC-3 Assembly programming.
•	Understand memory addressing and register management.
•	Implement stack-based subroutines.
•	Convert between ASCII and binary values.
•	Apply the Bubble Sort algorithm in a low-level environment.
Why We Undertook It
This project was completed to strengthen our understanding of assembly language programming and algorithm implementation using the LC-3 instruction set.
________________________________________
Technologies Used
•	LC-3 Assembly Language
•	LC-3 Simulator
•	Bubble Sort Algorithm
________________________________________
Features
•	Accepts 8 user-entered integers.
•	Supports multi-digit numbers from 0–100.
•	Converts ASCII keyboard input into binary values.
•	Stores values in memory using an array.
•	Sorts values using Bubble Sort.
•	Prints sorted results in ascending order.
•	Uses stack-based subroutines for modular design.
•	Includes separate input and output routines.
Example
Input:
11
8
2
17
6
4
3
21
Output:
2
3
4
6
8
11
17
21
________________________________________
Screenshots
Add screenshots of your LC-3 Simulator execution here.
Example:
![Program Execution](./img/screenshot.png)
________________________________________
Setup
Requirements
•	LC-3 Simulator
•	LC-3 Assembler
Installation
1.	Download and install an LC-3 Simulator.
2.	Open the simulator.
3.	Create a new assembly source file.
4.	Copy the contents of bubble_sort.asm into the file.
5.	Assemble the source code.
6.	Load the generated object file.
7.	Run the program.
________________________________________
Usage
When the program starts, enter eight integers.
⚠️ Important: Press Enter after each complete number, not after each digit.
Example:
11
8
2
17
6
4
3
21
After the eighth value is entered, the program automatically:
1.	Stores the numbers in memory.
2.	Sorts them using Bubble Sort.
3.	Displays the sorted results.
Main Components
INPUT_NUM Subroutine
•	Reads decimal input from the keyboard.
•	Converts ASCII digits into binary integers.
•	Supports multi-digit values.
•	Uses stack operations to preserve registers.
Bubble Sort Logic
•	Performs seven sorting passes.
•	Compares adjacent elements.
•	Swaps values when necessary.
•	Sorts the array in ascending order.
PRINT_NUM Subroutine
•	Converts binary integers to ASCII.
•	Handles values from 0–100.
•	Displays numbers to the console.
________________________________________
Project Status
Project Status: Complete
This program successfully reads, sorts, and displays eight integers using LC-3 Assembly.
________________________________________
Ideas for Improvement
Improvements
•	Add input validation for values outside the restricted range.
•	Support negative integers.
•	Optimize Bubble Sort with an early-exit flag.
•	Allow variable-sized arrays instead of a fixed size of eight.
Future Features
•	Support larger datasets.
•	Add user prompts and formatted output.
•	Display the array before and after sorting.
________________________________________
Acknowledgements
•	Developed for CIS -11.
•	Inspired by classic Bubble Sort implementations.
•	Thanks to the team for guidance and feedback.
•	Built using the LC-3 Assembly.________________________________________
Team Members
•	Bryant Martinez Fossati
•	Ryland Tolentino
•	Cassandra Suarez
________________________________________
Contact
Created by the Bubble Sort Sorcerers Team.
[Back to Top](#table-of-contents)
