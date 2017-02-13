[![General Assembly Logo](https://camo.githubusercontent.com/1a91b05b8f4d44b5bbfb83abac2b0996d8e26c92/687474703a2f2f692e696d6775722e636f6d2f6b6538555354712e706e67)](https://generalassemb.ly/education/web-development-immersive)

# HW Reading: Practical Object-Oriented Design in Ruby

[POODR](http://www.poodr.com/) (pronounced "pooder") explains object-oriented design (OOD) in Ruby. Javascript is an object-oriented language but it is not class-based like it is in Ruby, Java, C++, C, etc.. POODR was written by Sandi Metz, a software developer and author focused on writing flexible object-oriented code in Ruby and Rails.

## Exercise Objectives

- have fun reading material on programmatic thinking and design
- gain insight to programming languages from a design standpoint
- gain an intermediate level of understanding Ruby as a class-based language
- start thinking about the differences in Javascript and Ruby

## Directions

Read the first 3 chapters of POODR [available as a PDF here](https://github.com/edenzik/cs105b/blob/master/books/Practical%20Object-Oriented%20Design%20in%20Ruby.pdf) and answer the questions below.


### Short Answer Questions:

Answer should be no more than a couple of sentences. Refer to the reading.

1. According to Metz, what is Object-oriented design about?

Object-oriented design is about managing dependencies. It is a set of coding techniques that arrange dependencies such that objects can tolerate change.

2. What does SOLID stand for?

Single Responsibility, Open-Closed, Liskov Substitution, Interface Segregation, Dependency Inversion

3. Ruby is a class-based object-oriented language. What does that mean?

Ruby allows you to define a class that provides a blueprint for the construction of similar objects. A class defines methods and attributes.

4. Where are methods defined in Ruby?

In classes.

5. Why does single Responsibility matter?

A class that has more than one responsibility is difficult to reuse. If you want to reuse some (but not all) of its behavior, it's impossible to get at only the parts you need. Single-responsibility = easy to reuse.

6. What does `attr_reader` do?

It's an easy way to create the encapsulating/wrapper methods for variables.

7. What are 4 benefits Metz outlines for methods that have a single responsibility?

Expose previously hidden qualities avoid the need for comments, encourage reuse, are easy to move into another class.

8. What are 4 things an object knows when it has a dependency?

The name of another class. The name of a message that it intends to send to someone other than self. The arguments that a message requires. The order of those arguments.

9. Dependency management is core to creating future-proof applications. What does injecting dependencies and isolating dependencies do? What are their benefits?

Injecting Dependencies creates loosely coupled objects that can be reused in novel ways. Isolating dependencies allows objects to quickly adapt to unexpected changes.
