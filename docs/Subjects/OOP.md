
# OOP
# Question Pattern

Chapter 1 : Introduction to object oriented programming

Chapter 2 : Introduction to c++

Chapter 3 : C++ language constructs 

Chapter 4 : Objects and classes

Chapter 5 : Operator overloading 

Chapter 6 : Inheritance 

Chapter 7 : Polymorphism and dynamic binding

Chapter 8 : Stream Computation for console and file I/O

Chapter 9 : Templates

Chapter 10 : Execution Handling

---

Chapter 1,2,4 - 20 marks

Chapter 7,9,10 - 20 marks

Chapter 3,5,6,8 - 10 marks each

---

# Chapter 1 :
* Characteristics of OOP
* Differences between OOP and POP
* Limitations of POP
* Advantages / Disadvantages of OOP over POP 
* What is OOP?
* What is data abstraction?
* Compare data abstraction with encapsulation in C++
* Concept of class in C++
* Why OOP is necessary in programming 
* Is OOP better than structured programming? Why?
* PROGRAMS!!

---

# Chapter 2:
* Features of C++
* Advantage of C++ over C
* History of C++
* Different components (Lexical elements) of C++
* Need of C++

---

# Chapter 3:

## Theory:

* Explain how function selection is done in function overloading?
* Where can enumerated data types be used in C++ programming?
* How does an inline function differ from a pre-processor macro?
* Main advantage of passing argument by reference
* Explain the usage of ‘new’ and ‘delete’ operators for DMA
* Define inline function with its pros and cons
* Explain how the use of default argument supports the function overloading 
* What do you understand by default arguments
* How can you relate default argument function with function overloading?
* What is function overloading with examples?
* How is pass by reference done in C++ with suitable examples?
* What is Token, write its details?
* How can a function with default argument be implemented with function overloading. Show example
* Why default arguments are used with functions.
* Define DMA and how do you use it in C++
* Significance of reference variable with suitable example
* What is literals and identifier
* What do you mean by namespace and explain how it can be used

## Programs:
* WAP to find volume of different shapes using function overloading
* WAP a program to swap two numbers using pass by reference concept
* WAP to calculate and display the cube of integer, float and double number using function overloading
* WAP to join two strings using dynamic constructor concept


---

# Chapter 4:
## Theory:
* Order of constructor and destructor invocation with example
* Use of static data member and static function in a class with example
* Define constructor and destructor
* Different types of constructor with examples
* Properties of constructor 
* Differences between copy constructor and assignment operator 
* A friend function is not a member of any classes but has full access to the members of class where it is declared as friend.
* Task of const keyword
* Can we have more than one constructor in a class? Explain
* Necessity of copy constructor with examples
* Constant function and its relation with constant object
* Necessity of friend function
* How any member function of a class can be friend of other class , explain with example
* Define “this” pointer with its applications 
* Why don’t you use an object to call the static member function, explain with an example?
* Why do you need to use reference in the argument to the copy constructor?
* Necessity of constructor
* Dynamic memory allocation for object and object array
* Difference between constructor and destructor
* Dynamic memory allocation
* Friend function and friend class 


## Programs:


# Chapter 5:

## Theory:
* Define operator overloading
* Need of operator overloading 
* Overloading operator using member function and non member function
* Binary and unary operator overloading along with their syntax and example
* Data conversion from one type to another
* Disadvantages of using operator overloading
* List of operators that can’t be overloaded in C++
* Explicit constructor with an example 
* Overloading relational operator using member function and nonmember function
* Syntax of operator overloading for various case
* Rules of operator overloading 
* Overriding differs from overloading, how?


## Programs:

* WAP to overload relational operators(==, !=, >,&lt;,>=,&lt;=) to compare complex numbers
* WAP to add two matrices by overloading + operator
* WAP to define a class distance with necessary data members and functions then overload the relational operators to compare the two objects of Distance class
* WAP having a class to represent money,the class should have two integer members to represent rupees and paisa. Overload + and - operators for adding and subtracting the objects , then overload >, &lt; , == and !+ operators for comparing the objects
*  Write a program to convert currency from dollar to rupees and vice versa (assume suitable data).
* WAP using a class to with 3 * 3 matrix as a data member. Overload the * operator so as to multiply two matrices
* Write a program that will convert object from a class Rectangle to object of a class Polar using Casting Operator.
* Create a class named city that will have two member variables cityname (char[20]) and distfromktm (float). Add member function to set and retrieve the cityname and distfromktm separately. Add operator overloading to find the distance between the cities (just find the difference of distfromktm) and sum of distance of those cities from kathmandu. In main function, initialize three city objects.Set the first and second city to be pokhara and dhangadi .display the sum of distfomktm of pokhara and dhangadi and distance between pokhara and dhangadi
* WAP to overload the relational operators to compare the length (in meter and centimeter) of two objects
* Write operator functions as member function of a class to overload arithmetic operator +, logical operator ‘&lt;=’ and stream operator ‘&lt;<’ to operate on the objects of user defined type time (hr, min, sec)
* WAP to concatenate two user given string by overloading binary plus(+) operator
* Create a class called time that has separate int member data for hours, minutes and second. One constructor should initialize this data to zero(0), and another should initialize it to fixed values. A member function should display it in 10:45:30 format. The final member function should add two objects of type time passed as arguments using operator overloading.
* Write a class that represent the distance class and overload ++ and – operator to increment and decrement distance
* WAP that converts object of celsius type to object of fahrenheit type
* Write a program to overload relational operators ( &lt;, >=, &lt;=) to compare complex numbers.

* Write a program to  define a Class Distance with necessary data members and functions. Then overload the relational operators to compare the two objects of Distance class.
* 

# Chapter 6:
## Theory:
* Types of inheritance
* Need of virtual base class with example
* Forms of inheritance with example of each
* Need and importance of inheritance 
* Ambiguity problem in multiple inheritance
* Details on member function overriding
* Ambiguity and function overriding , define and how can they be resolved, examples
* Use of scope resolution with overridden function
* Accessing every overridden function from derived class with example
* Need of virtual base class
* Access specifier and its types with syntax
* Constructor and destructor invocation order in single and multiple inheritance
* Show how parameterized base class constructor is called when derived class object are created
* Different types of derivation affecting the members of class

## Programs:

* WAP to demonstrate example of hierarchical inheritance
* WAP which contains a base class that ask the user to enter a complex number and make a derived class that adds the complex number of its own with the base. Finally make third class that is friend of derived and calculate the difference of base complex number and it’s own complex number
* WAP to show order of constructor invocation in multiple inheritance
* 
* 

# Chapter 7

* Need of virtual function with example
* Run time type information (RTTI)
* Use of dynamic_cast and typeid operators to achieve RTTI (imp)
* Define:  virtual function, pure virtual functions, abstract class, polymorphic class
* Abstract class and its uses
* Task of reinterpret_cast operator
* Reason for member function overriding when using virtual function
* Need of virtual destructor, with example
* Compile time and runtime binding
* Differentiate abstract base class and concrete class
* Role of virtual functions in c++ to cause dynamic polymorphism, how is it diff from the compile time polymorphism
* RTTI mechanism
* Use of pure virtual function


# Chapter 8 (File Handling)
## Theory:

* Write down the different techniques for formatting i/0 stream with example.
*  Explain the different errors encountered during file operation.
* What do you mean by manipulators? Explain different manipulators available in C++.
* List the features that are used in formatting the output. Explain each wiith example:
* Explain class hierarchy for console and file I/O with diagram.
* What are different ios class function and flags that are used for formatted I/O operation?
* Stream class hierarchy
* List any four formatting flags of ios class with their usage. Explain with an example how a non- parameterized user-defined manipulator can be defined. 
* Explain how do you achieve random access to file
* Discuss about classes for file stream operator with suitable block diagram
* File access pointer and manipulator
* Stream manipulator


## Program

* Write a program that stores information of students in a file and display the file's content in descending order according to their marks obtained.
* Write a program to read and write information of 10 students in a file
* Write a program for transaction processing that write
* and read objects randomly to and from a random access file so that the user can add, update, delete and display the account information (accountnumber, lastname, firstname, totalbalance).
* Write a program to make the billing system of a department store. Your program should store and retrieve data to/from files. Use manipulators to display the record in proper formats.
* Write a program to store and retrieve the information of Client(Client_ID, Account_ll), name, address and age) in the Bank management system. Also calculate the total number of clients in a bank
* Write a program to write records of N numbers of students into the file. And your program should search complete information of students from a file according to the CRN entered by the user and display it.


# Chapter 9(Templates)
## Theory:

* Define class template and function template with respective syntax. 
* Importance of function template and class template
* How can default arguments be used in class template
* Use of function template with multiple template types with examples
* Use of function template
* Function template overloading with example
* Case when all the template parameters are not used in function arguments


## Program

*  Write a program that will find the sum and average of elements in an array using function templates.
* Write a program for manåsing a simple library database. The information to be stored in the database are book id, book name, borrower's id, borrower's name, issue date and due date. Your program should have features to add a record, display all the records and display a set of records corresponding to a particular borrower's id or a particular borrower's name.
* Write a program using template to add two integers, two floats and one integer and one float respectively. Display the final result in float.


# Chapter 10 
## Theory:

* What are the different exception handling techniques in C++? Explain with appropriate examples.
* How is exception handling better than conventional/traditional error handling?
* Handling of multiple exceptions with example
* Advantages of exception handling
* Exception handling constructs:tasks of try, catch and throw block
* How do you throw only specified exception from a function, exemplify
* What do you understand by rethrowing an exception and catching all exceptions


## Programs :
* Define a class to represent time. It should have a member function to read time from the user and a member function to display the time. The function to read time must raise an exception if the user enters invalid values for hours, minutes or seconds. The exception throws should contain arguments. The exception should be handled outside cf the member function of the class.
* Write a program to find the square root of given number. Check the validity of input number and raise the exception as per requirement.
* Write a program to read your Date of Birth and display it. Your program should throw multiple exceptions for day, month and other values not in range using exception Class and catch exception is handled by a separate handler.
*  Write a program to create a class to represent stack data structure and use exception handling to control empty and full cases.
