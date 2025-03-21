# Patika & Getir Java Spring Boot Bootcamp HW-1

## Why we need to use OOP? Some major OOP languages?

Object oriented programming enhances the organization and reusability of our code and it makes the code easy to understand. It simplifies the management of complex projects. Some OOP languages are C++, Java, C# etc.

## Interface vs Abstract class?

An interface requires a class to include certain functionalities that can be used in various situations. When a class implements an interface, it must specify all the methods outlined in that interface.

On the other hand, an abstract class provides some methods while leaving others for its subclasses to define. This is beneficial for sharing common behaviors while still giving subclasses the freedom to handle specific scenarios.

## Why we need equals and hashcode? When to override?

The equals() method compares the memory addresses of the objects which means even if two objects appear identical they may not be considered equal. On the other hand, the hashCode() method is used for looking for objects within collections such as HashMap.

If we choose to override the equals() method, it is essential to also override the hashCode() method to ensure that our objects are handled correctly within data structures.

## Diamond problem in Java? How to fix it?

It occurs when a class derives the same method from two distinct parent classes. It causes uncertainty about which method to use. Java prevents this problem by prohibiting multiple inheritance in classes. If it occurs with interfaces we can solve it by overriding the conflicting default methods.

## Why we need Garbage Collector? How does it run?

It acts as an automatic maintenance team for memory. It eliminates items that are no longer needed to create more space. Java executes it automatically, but if we want to make it manually we can use System.gc().

## Java ‘static’ keyword usage?

We can use static keyword with variables, classes, and imports.

- **Static variables** are variables that are associated with the class rather than with specific instances. Every instance of the class has the identical value.
- **Static method** is a part of the class and can be invoked without instantiating an object. Static methods are unable to directly access non-static variables.
- In Java we can import static members from other classes so that we can use them without class names.

## Immutability means? Where, How and Why to use it?

An object is considered immutable if its state cannot change after it is constructed.

We can use immutability in:

- **String class**: Any modification leads to creation of a new String object.
- **Wrapper classes**: Integer, Double, Character, etc., are immutable.

## Composition and Aggregation means and differences?

- **Composition**: A relationship where one object cannot exist without the other. A car and its engine.
- **Aggregation**: A relationship where objects can exist independently. A university and its students.

## Cohesion and Coupling means and differences?

- **Cohesion** is a term which is used for how focused a class is on a single purpose. High cohesion is better because it helps to write clean code.
- **Coupling** is a term which is used for how dependent a class is on other classes. Low coupling is better because this means if we want to change something in the code we can make it without breaking everything.

## Heap and Stack means and differences?

- **Stack** is smaller and faster, used for holding method calls and local variables.
- **Heap** is larger and slower, used for holding objects. The Garbage Collector primarily operates in the heap.

## Exception means? Type of Exceptions?

An exception is an unexpected occurrence while the program is running and Java uses the Exception object to handle errors and other exceptional events.

There are mainly two types of exceptions in Java as:
- **Checked Exception** (compile time)
- **Unchecked Exception** (runtime)

## How to summarize ‘clean code’ as short as possible?

Clean code is writing code in a way that everyone can easily read and understand, not just the person who writes it.

## What is the method of hiding in Java?

When static methods in a superclass and a subclass have the same type and signature, the method in the subclass hides the method in the superclass.

## What is the difference between abstraction and polymorphism in Java?

- **Abstraction**: Keeping implementation details hidden and only displaying the user-relevant functionality. It allows you to focus on what an object does, instead of how it does.
- **Polymorphism**: The ability of an object to have different forms is called polymorphism. In Java, polymorphism allows the behavior of a call that can vary depending on the object of calling it.
