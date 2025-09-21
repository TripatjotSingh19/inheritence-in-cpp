# Inheritance in C++
# Aim
To understand and implement different types of inheritance in C++, exploring how classes can reuse and extend functionality through hierarchical relationships.

# Theory
Inheritance is one of the core concepts of Object-Oriented Programming (OOP).

It allows a class (called the derived class) to acquire the properties and behaviors of another class (called the base class).

# Key Points
Base Class: The class whose members are inherited.

Derived Class: The class that inherits from the base class.

Access Specifiers:

    public → Public & protected members of base remain accessible.
    protected → Public & protected members of base become protected.
    private → Public & protected members of base become private.

 # Types of Inheritance
# Single Inheritance

One base class → One derived class.
Example: Vehicle → Car.

# Multilevel Inheritance

A class derived from another derived class.
Example: University → Department → Lab.

# Hierarchical Inheritance

Multiple classes inherit from the same base class.
Example: University → Department, Hostel, Library.

# Multiple Inheritance

A class inherits from more than one base class.
Example: Department → University + Facility.

# Hybrid Inheritance

Combination of two or more types (e.g., hierarchical + multiple).

# Algorithms
