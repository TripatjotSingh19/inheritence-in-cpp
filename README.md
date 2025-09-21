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
# Single Inheritance
        Start
        Define a base class Vehicle with a method color().
        Define a derived class Car that inherits from Vehicle and adds speed().
        In main():
        Create object myCar.
        Call color() and speed().
        End
# Multilevel Inheritance
        Start
        Define base class University with showUni().
        Define derived class Department inheriting University, with showDept().
        Define derived class Lab inheriting Department, with showLab().
        In main():
        Create object VLSI.
        Call all three methods.
        End
# Hierarchical Inheritance
        Start
        Define base class University.
        Define three derived classes: Department, Hostel, Library.
        Each derived class has its own method.
        In main():
        Create objects of each derived class.
        Call base + derived methods.
        End
# Multiple Inheritance
        Start
        Define base class University.
        Define base class Facility.
        Define derived class Department inheriting from both.
        In main():
        Create object ec.
        Call methods from both base classes + derived class.
        End
# Hybrid Inheritance
        Start
        Combine hierarchical + multiple inheritance.
        Example: University as base.
        Department and Hostel inherit from University.
        Lab inherits from Department and also uses Facility.
        In main():
        Create objects and demonstrate combined features.
        End
# Conclusion
This experiment demonstrates the power of inheritance in C++:
