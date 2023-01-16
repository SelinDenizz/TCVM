# TCVM
Corporate-Vulnerability-Management-System
In this vulnerability database system, object-oriented programming (OOP) principles have been applied to design and implement the system in a modular and efficient manner.
The system is comprised of three main classes: User, Authorized, and Unauthorized.
The User class is the base class that contains all the common attributes and methods that are required for the system to function. 
The private attributes of the class include the username and password for authentication, the CVE number to find related information, and the mail address used for two-factor-authentication.
The public methods of the class include accessor functions to get the username and password attributes, setters to assign the username and password attributes, a function to obtain the CVE number from the user, a function to search the CVE number in the database, a function to read the related data, a function to write the related data, a function to obtain the mail address, a function to check the username and password for authentication, a function to determine whether the user wants to read about new publicly released attacks, and a friend function to overload the outstream variable to print all attributes of a User class object.
In the Authorized class, the write function is overridden to allow authorized users to change the database.
In the Unauthorized class, the write function is overridden to inform unauthorized users that they do not have access to the records.
Additionally, an InvalidInputException class is also implemented to handle invalid inputs and inform the user of the correct format to input their information.
The system uses various OOP principles such as encapsulation, inheritance, polymorphism, and exception handling.
Encapsulation ensures that the private attributes and methods of the classes are protected and only accessible through the public methods.
Inheritance allows the Authorized and Unauthorized classes to inherit the attributes and methods of the User class.
Polymorphism allows the overridden write functions in the Authorized and Unauthorized classes to have the same function signature but different implementations.
Exception handling allows the program to handle any invalid inputs and inform the user of the correct format.
In summary, this vulnerability database system uses OOP principles to design and implement a secure and efficient system that can authenticate users, search and read information from the database, and allow authorized
