# Java object-oriented programming & DSA repo

## OOP Concepts in Java
As the name suggests OOP refers to languages that use objects in programming, they use objects as a primary source to implement what is 
to happen in the code. Objects are seen by the viewer or user performing tasks assigned by you. OOP aims to implement real-world entities 
like inheritance, hiding, polymorphism etc. in programming. The main of OOP is to bind together the data and the functions that operated on 
the so that no other part of the code can access this data except that function.

Let us discuss prerequisites by polising concepts of method declaration and message passing. Starting off with the method declaration, it consists
of six components:

### Access Modifier
Defines the access type of the method i.e. from where it can be accessed in your application. In Java, there are 4 types of access specifiers:
1. public: accessible to all classes in your function
2. protected: accessible within the package in which it is defined and in its subclass(es) (including subclasses outside the package).
3. private: accessible only within the class in which it is defined 
4. default(declared / defined without using any modifier): Accessible withing the same class and package within which its class is defined.

### Return Type 
The data type of the value returned by the method or void if it does not return a value. 

### Method Name
The rules for field names apply to method names as well, but the convention is a little different

### Parameter list
Comma-separated list of the input parameters that are defined, preceded by their data type, within the enclosed parentheses. If there are no parameters, you must use empty parentheses ().

### Exception list
The exceptions you expect the method to throw. YOu can specify these exceptions(s).

### Method body
It is the block of code enclosed between braces, that you need to execute to perform you intended operations.

### 4 Pillars of Java

1. Abstraction: Data Abstraction is the property by virtue of which only the essential details are displayed to the user. The trivial or non-essential units are not displayed to the user. Ex: A car is viewed as a car rather than its individual components.
   Data Abstraction may also be defined as the process of identifying only the required characteristics of an object, ignoring the irrelevant details. The properties and behaviors of an object differentiate it from other objects of similar type and also help in classifying/grouping the object. In java abstraction is achieved by interfaces or abstract classes.
2. Encapsulation: It is defined as the wrapping up of data under a single unit. It is the mechanism that binds together the code and the data it manipulates. Another way to think about encapsulation is that it is a protective shield that prevents the data from being accessed by the code outside this shield. 
3. Inheritance: Inheritance is an important pillar of OOP. It is the mechanism in Java by which one class is allowed to inherit the features (fields and methods) of another class. We are achieving inheritance by using extends keyword. Inheritance is also known as “is-a” relationship.
Let us discuss some frequently used important terminologies:
Superclass: The class whose features are inherited is known as superclass (also known as base or parent class).
Subclass: The class that inherits the other class is known as subclass (also known as derived or extended or child class). The subclass can add its own fields and methods in addition to the superclass fields and methods.
Reusability: Inheritance supports the concept of “reusability”, i.e. when we want to create a new class and there is already a class that includes some of the code that we want, we can derive our new class from the existing class. By doing this, we are reusing the fields and methods of the existing class.
4. Polymorphism: Allows you to differentiate between the entities of the same name. ex: sleep(1000), sleep(1000,2000)
Polymorphism is mainly of two types: 
   1. OverLoading
   2. OverRiding


