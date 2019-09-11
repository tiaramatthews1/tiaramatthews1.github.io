---
layout: post
title:      "Object Orientation"
date:       2019-09-11 00:57:34 +0000
permalink:  object_orientation
---


**Object-oriented programming** is a programming paradigm based on the concept of "objects", which can contain data, in the form of fields, and code, in the form of procedures. 
There are many different characteristics of object-oriented programming:
 
** **Encapsulation**** is defined as the wrapping up of data under a single unit. It is the mechanism that binds together code and the data it manipulates.Other way to think about encapsulation is, it is a protective shield that prevents the data from being accessed by the code outside this shield. As in encapsulation, the data in a class is hidden from other classes, so it is also known as data-hiding.

Example:

If we have a picture of an regular pharmaceutical pill, above the pill would be the encapsulation. Inside the pill would be the variables data and below the pill would be the class.
 
**Data Abstraction** is the property by virtue of which only the essential details are displayed to the user.The trivial or the non-essentials units are not displayed to the user. 

Example: A car is viewed as a car rather than its individual components.

Data Abstraction may also be defined as the process of identifying only the required characteristics of an object ignoring the irrelevant details.
 
**Inheritance** is an important pillar of OOP(Object Oriented Programming). It is the mechanism in java by which one class is allow to inherit the features(fields and methods) of another class. A key word used for inheritance is extends.

Example: 

class derived-class extends base-class  
{  
   //methods and fields  
}  
 
 **Polymorphism** means having many forms. In simple words, we can define polymorphism as the ability of a message to be displayed in more than one form.
 
 For example: 
 
 // This class will contain 
// 3 methods with same name, 
// yet the program will 
// compile & run successfully 
public class Sum { 
  
    // Overloaded sum(). 
    // This sum takes two int parameters 
    public int sum(int x, int y) 
    { 
        return (x + y); 
    } 
  
    // Overloaded sum(). 
    // This sum takes three int parameters 
    public int sum(int x, int y, int z) 
    { 
        return (x + y + z); 
    } 
  
    // Overloaded sum(). 
    // This sum takes two double parameters 
    public double sum(double x, double y) 
    { 
        return (x + y); 
    } 
  
    // Driver code 
    public static void main(String args[]) 
    { 
        Sum s = new Sum(); 
        System.out.println(s.sum(10, 20)); 
        System.out.println(s.sum(10, 20, 30)); 
        System.out.println(s.sum(10.5, 20.5)); 
    } 
} 

Output: 
30
60
31.0
 
 **Classes** is an  basic concept of Object Oriented Programming which revolve around the real life entities. Objects also works as one of these concepts as well. It represents the set of properties or methods that are common to all objects of one type.
 
 Example: Inside the classes are
 
**Modifiers**: A class can be public or has default access (Refer this for details).

**Class name**: The name should begin with a initial letter (capitalized by convention).

**Superclass**(if any): The name of the class’s parent (superclass), if any, preceded by the keyword extends. A class can only extend (subclass) one parent.

**Interfaces**(if any): A comma-separated list of interfaces implemented by the class, if any, preceded by the keyword implements. A class can implement more than one interface.
Body: The class body surrounded by braces, { }.
 
 **Objects** is an basic concept of Object Oriented Programming which revolve around the real life entities. Classes also works as one of these concepts as well. 
 
 Objects consists of state, behavior, and identity.
 
 Example:
 
 An object would be a dog. We know the identity is the name of the dog. The state/attributes would be the breed, age, and color. The behaviors would be bark, sleep, eat.
 
 **Method** is a collection of statements that perform some specific task and return the result to the caller. A method can perform some specific task without returning anything. Methods allows us to reuse the code without retyping the code.
 
Methods have six components: access modifier, return type, method name, parameter list, exception list, and the method body.

For example: https://www.geeksforgeeks.org/object-oriented-programming-oops-concept-in-java/
 
 **Message Passing** is communication between processes. It is a form of communication used in object-oriented programming as well as parallel programming. A message for an object is a request for execution of a procedure and therefore will invoke a function in the receiving object that generates the desired results. Message passing involves specifying the name of the object, the name of the function and the information to be sent. There is no example because it is simply just that.
 
 
 






