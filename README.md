# OOP Questions for the interview
50 question will help you to know how to answer in the interview when you asked about object orianted programming OOP.

## 1. What is OOPS?

OOPS is abbreviated as Object Oriented Programming system in which programs are considered as a collection of objects. Each object is nothing but an instance of a class.

## 2. Write basic concepts of OOPS?

Following are the concepts of OOPS and are as follows:
Abstraction. 
Encapsulation. 
Inheritance. 
Polymorphism. 

## 3. What is a class?

A class is simply a representation of a type of object. It is the blueprint/ plan/ template that describe the details of an object.


## 4. What is an object?

Object is termed as an instance of a class, and it has its own state, behavior and identity.


## 5. What is Encapsulation?

Encapsulation is an attribute of an object, and it contains all data which is hidden. That hidden data can be restricted to the members of that class.

Levels are Public, Protected, Private, Internal and Protected Internal.


## 6. What is Polymorphism?

Polymorphism is nothing but assigning behavior or value in a subclass to something that was already declared in the main class. Simply, polymorphism takes more than one form.


## 7. What is Inheritance?

Inheritance is a concept where one class shares the structure and behavior defined in another class. If inheritance applied on one class is called Single Inheritance, and if it depends on multiple classes, then it is called multiple Inheritance.


## 8. What are manipulators?

Manipulators are the functions which can be used in conjunction with the insertion (<<) and extraction (>>) operators on an object. Examples are endl and setw.


## 9. Define a constructor?

Constructor is a method used to initialize the state of an object, and it gets invoked at the time of object creation. Rules for constructor are:
Constructor Name should be same as class name. 
Constructor must have no return type. 


## 10. Define Destructor?

Destructor is a method which is automatically called when the object is made of scope or destroyed. Destructor name is also same as class name but with the tilde symbol before the name.


## 11. What is Inline function?

Inline function is a technique used by the compilers and instructs to insert complete body of the function wherever that function is used in the program source code.


## 12. What is a virtual function?

Virtual function is a member function of class and its functionality can be overridden in its derived class. This function can be implemented by using a keyword called virtual, and it can be given during function declaration.


Virtual function can be achieved in C++, and it can be achieved in C Language by using function pointers or pointers to function.


## 13. What is friend function?

Friend function is a friend of a class that is allowed to access to Public, private or protected data in that same class. If the function is defined outside the class cannot access such information.

Friend can be declared anywhere in the class declaration, and it cannot be affected by access control keywords like private, public or protected.


## 14. What is function overloading?

Function overloading is defined as a normal function, but it has the ability to perform different tasks. It allows creation of several methods with the same name which differ from each other by type of input and output of the function.

Example
void add(int& a, int& b);
void add(double& a, double& b);
void add(struct bob& a, struct bob& b);


## 15. What is operator overloading?

Operator overloading is a function where different operators are applied and depends on the arguments. Operator,-,* can be used to pass through the function, and it has their own precedence to execute.

Example:
class complex {
double real, imag;

public:
complex(double r, double i) :
real(r), imag(i) {}
complex operator+(complex a, complex b);
complex operator*(complex a, complex b);
complex& operator=(complex a, complex b);
}

a=1.2, b=6


## 16. What is an abstract class?

An abstract class is a class which cannot be instantiated. Creation of an object is not possible with abstract class , but it can be inherited. An abstract class can contain only Abstract method.


## 17. What is a ternary operator?

Ternary operator is said to be an operator which takes three arguments. Arguments and results are of different data types, and it is depends on the function. Ternary operator is also called as conditional operator.


## 18. What is the use of finalize method?

Finalize method helps to perform cleanup operations on the resources which are not currently used. Finalize method is protected, and it is accessible only through this class or by a derived class.


## 19. What are different types of arguments?

A parameter is a variable used during the declaration of the function or subroutine and arguments are passed to the function, and it should match with the parameter defined. There are two types of Arguments. 
Call by Value – Value passed will get modified only inside the function, and it returns the same value whatever it is passed it into the function. 
Call by Reference – Value passed will get modified in both inside and outside the functions and it returns the same or different value. 


## 20. What is super keyword?


Super keyword is used to invoke overridden method which overrides one of its superclass methods. This keyword allows to access overridden methods and also to access hidden members of the superclass.

It also forwards a call from a constructor to a constructor in the superclass.


## 21. What is method overriding?

Method overriding is a feature that allows sub class to provide implementation of a method that is already defined in the main class. This will overrides the implementation in the superclass by providing the same method name, same parameter and same return type.


## 22. What is an interface?

An interface is a collection of abstract method. If the class implements an inheritance, and then thereby inherits all the abstract methods of an interface.


## 23. What is exception handling?

Exception is an event that occurs during the execution of a program. Exceptions can be of any type – Run time exception, Error exceptions. Those exceptions are handled properly through exception handling mechanism like try, catch and throw keywords.


## 24. What are tokens?

Token is recognized by a compiler and it cannot be broken down into component elements. Keywords, identifiers, constants, string literals and operators are examples of tokens.

Even punctuation characters are also considered as tokens – Brackets, Commas, Braces and Parentheses.


## 25. Difference between overloading and overriding?

Overloading is static binding whereas Overriding is dynamic binding. Overloading is nothing but the same method with different arguments , and it may or may not return the same value in the same class itself.

Overriding is the same method names with same arguments and return types associates with the class and its child class.


## 26. Difference between class and an object?

An object is an instance of a class. Objects hold any information , but classes don’t have any information. Definition of properties and functions can be done at class and can be used by the object.

Class can have sub-classes, and an object doesn’t have sub-objects.


## 27. What is an abstraction?

Abstraction is a good feature of OOPS , and it shows only the necessary details to the client of an object. Means, it shows only necessary details for an object, not the inner details of an object. Example – When you want to switch On television, it not necessary to show all the functions of TV. Whatever is required to switch on TV will be showed by using abstract class.


## 28. What are access modifiers?

Access modifiers determine the scope of the method or variables that can be accessed from other various objects or classes. There are 5 types of access modifiers , and they are as follows:. 
Private. 
Protected. 
Public. 
Friend. 
Protected Friend. 

## 29. What is sealed modifiers?

Sealed modifiers are the access modifiers where it cannot be inherited by the methods. Sealed modifiers can also be applied to properties, events and methods. This modifier cannot be applied to static members.

## 30. How can we call the base method without creating an instance?

Yes, it is possible to call the base method without creating an instance. And that method should be,.

Static method.
Doing inheritance from that class.-Use Base Keyword from derived class.

## 31. What is the difference between new and override?

The new modifier instructs the compiler to use the new implementation instead of the base class function. Whereas, Override modifier helps to override the base class function.

## 32. What are the various types of constructors?

There are three various types of constructors , and they are as follows:.

- Default Constructor – With no parameters.

- Parametric Constructor – With Parameters. Create a new instance of a class and also passing arguments simultaneously.

- Copy Constructor – Which creates a new object as a copy of an existing object.

## 33. What is early and late binding?

Early binding refers to assignment of values to variables during design time whereas late binding refers to assignment of values to variables during run time.

## 34. What is ‘this’ pointer?

THIS pointer refers to the current object of a class. THIS keyword is used as a pointer which differentiates between the current object with the global object. Basically, it refers to the current object.

## 35. What is the difference between structure and a class?

Structure default access type is public , but class access type is private. A structure is used for grouping data whereas class can be used for grouping data and methods.
Structures are exclusively used for dataand it doesn’t require strict validation , but classes are used to encapsulates and inherit data which requires strict validation.

## 36. What is the default access modifier in a class?

The default access modifier of a class is Private by default.

## 37. What is pure virtual function?

A pure virtual function is a function which can be overridden in the derived class but cannot be defined. A virtual function can be declared as Pure by using the operator =0.
Example:

Virtual void function1() // Virtual, Not pure
Virtual void function2() = 0 //Pure virtual

## 38. What are all the operators that cannot be overloaded?

Following are the operators that cannot be overloaded -. 
Scope Resolution (:: ) 
Member Selection (.) 
Member selection through a pointer to function (.*) 

## 39. What is dynamic or run time polymorphism?

Dynamic or Run time polymorphism is also known as method overriding in which call to an overridden function is resolved during run time, not at the compile time. It means having two or more methods with the same name,same signature but with different implementation.

## 40. Do we require parameter for constructors?

No, we do not require parameter for constructors.

## 41. What is a copy constructor?

This is a special constructor for creating a new object as a copy of an existing object. There will be always only on copy constructor that can be either defined by the user or the system.

## 42. What does the keyword virtual represented in the method definition?

It means, we can override the method.

## 43. Whether static method can use non static members?

False

## 44. What are base class, sub class and super class?

Base class is the most generalized class , and it is said to be a root class.

Sub class is a class that inherits from one or more base classes.

Super class is the parent class from which another class inherits.

## 45. What is static and dynamic binding?

Binding is nothing but the association of a name with the class. Static binding is a binding in which name can be associated with the class during compilation time , and it is also called as early Binding.

Dynamic binding is a binding in which name can be associated with the class during execution time , and it is also called as Late Binding.

## 46. How many instances can be created for an abstract class?

Zero instances will be created for an abstract class.

## 47. Which keyword can be used for overloading?

Operator keyword is used for overloading.

## 48. What is the default access specifier in a class definition?

Private access specifier is used in a class definition.

## 49. Which OOPS concept is used as reuse mechanism?

Inheritance is the OOPS concept that can be used as reuse mechanism.

## 50. Which OOPS concept exposes only necessary information to the calling functions?

Data Hiding / Abstraction
