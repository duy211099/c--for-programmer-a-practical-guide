# 1. What is C# ?
## Features of C#
Similar to Java it is:
- Object-Oriented
- Comes with an extensive class library
- Mutiple types of polymorphism
- Separation of interfaces from implementations
## Uses of C#

# 2. Hello World!
## The "using" Directive
- It declares that the current file can use members of the indicated namespace without using the member's fully qualified name.
## Class

# 10. Variable Casting
```(type)name```

# 65. What is Inheritance?
- Provides a way to create a new class from an existing class
- New class is a specialized version of the existing class
- Allows the new class to overloadmethods from the existing class.
## Terminology
- Base Class(or Parent): inherited by child class.
- Derived Class(or child): inherits from base class.
## Characteristics 
A **derived** class has:
- All members defined in the derived class.
- All members declared in the base class.
A **derived** class can:
- Use all public members defined in the derived class.
- Use all public members defined in the base class.
- Override an inherited member

# 71. Polymorphism 
## Polymorphism
The term Polymorphism means the ability to take many forms. It occurs ifthere is a hierarchy of classes which are all related to each other byinheritance.
## Virtual Methods 
A virtualmethod is a member function which is declared in the base classusing the keywordvirtual and is re-defined (Overriden) by the derived class.
**Note**: To override a virtualmethod, use the keywordoverride
Virtual functions can be used while implementing Polymorphism