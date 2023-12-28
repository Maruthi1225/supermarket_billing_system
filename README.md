# supermarket_billing_system1. Introduction
The Supermarket Billing System is a console-based application written in C++ that simulates a billing system for a supermarket. It allows users to perform various tasks such as generating bills, adding, removing, and editing item details, and displaying item details. The system uses file handling to store and retrieve item information.
2. Code Overview
2.1.
Libraries Used:
▪
iostream: Input/output stream handling.
▪
windows.h: Windows-specific library for console manipulation.
▪
conio.h: Console input/output functions.
▪
fstream: File stream for reading and writing to files.
▪
cstring: C-style string manipulation functions.
▪
cstdio: C standard input/output functions.
▪
cstdlib: C standard library functions.
▪
iomanip: Input/output manipulators for formatting.
2.2.
Global Variables:
▪
k, r, flag: Global variables used for formatting and tracking.
▪
coord: Global variable for console cursor position.
▪
fout, fin: File stream objects for writing and reading.
2.3.
Structures:
▪
date: Represents the date with day, month, and year.
2.4.
Classes
2.4.1.
item Class
▪
Represents an item in the supermarket. Data members:
▪
itemno, name, date.
Member functions:
▪
add(): Adds item details.
▪
show(): Displays item details.
▪
report(): Displays item details for reporting.
▪
retno(): Returns the item number.
2.4.2.
amount Class
▪
Inherits from the item class.
▪
Represents the amount details (price, quantity, tax, etc.).
▪
Data members: price, qty, tax, gross, dis, netamt.
▪
Member functions:
▪
add(): Adds amount details.
▪
calculate(): Calculates net amount.
▪
show(): Displays amount details.
▪
report(): Displays amount details for reporting.
▪
pay(): Displays payment details.
▪
retnetamt(): Returns the net amount.
2.5.
Functions
▪
gotoxy(int x, int y): Sets the console cursor position.
▪
main(): The main function containing the application logic.
2.6.
File Handling
▪
The program uses file handling to store and retrieve item information. Items are stored in a binary file named itemstore.dat.
3. Concepts Used
3.1.
Object-Oriented Programming (OOP)
▪
The program follows OOP principles by using classes (item and amount) to encapsulate related data and functionality.
3.2.
File Handling
▪
File handling is employed to store and retrieve item details in a binary file (itemstore.dat).
3.3.
Console Manipulation
▪
The windows.h library is used for console manipulation, allowing control over the console window and cursor position.
3.4.
Inheritance
▪
The amount class inherits from the item class, demonstrating the concept of inheritance.
3.5.
Data Encapsulation
▪
Data encapsulation is achieved through private and public members of classes, enforcing data hiding and abstraction.
4.
Execution Flow
▪
The program starts by presenting a menu to the user.
▪
Users can choose options like generating bills, editing item details, and displaying item details.
▪
Data is stored and retrieved using file handling.
▪
The program utilizes loops and switches for user interaction.
5. Conclusion
The Supermarket Billing System is a simple yet comprehensive console
application demonstrating concepts of object-oriented programming, file handling,
and console manipulation. It provides basic functionalities expected in a supermarket billing system.
This documentation aims to provide a comprehensive understanding of the code structure, concepts used, and execution flow.
THANK YOU
