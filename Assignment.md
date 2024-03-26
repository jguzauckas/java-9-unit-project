For this project, we will try to set up a hierarchy of classes, similar to our Media example from class. This project is open-ended in terms of what you choose as a theme/topic for your hierarchy, though I have provided a few examples [here](https://docs.google.com/document/d/1Znj77zdgbvKQ-DgtZPK4hXILk3vVWlULSU7x_6WiIeY/edit?usp=sharing) that you can choose from and utilize if you want.

Regardless of your theme/topic, here are the overarching requirements for your hierarchy:
- All subclasses must have an “is-a” relationship with their superclass (i.e., “All books are media, but not all media are books)
- One top-level superclass (i.e., Media from in class)
- At least 4 levels of classes (4 levels in the diagram, note that all of my examples give you 3 levels, so even if you choose one of those, you will need an additional level).
- Each level needs to have a minimum number of classes (note that all of my examples give you less than this minimum number, so even if you choose one of those, you will need more classes):
    - Top-Level - 1 Class
    - Second Level - 4 Classes
    - Third Level - 8 Classes
    - Fourth Level - 4 Classes
- In the Top and Second Level, each class should have at least one subclass:
    - Top-Level - Minimum 3 Subclasses (All Second-Level classes should be subclasses of the Top Level)
    - Second Level - Minimum 1 Subclass
    - Third Level - Only some classes need to have a subclass from the Fourth Level
- A Runner Class that has adequate testing of all classes and methods, including some testing for Polymorphism, where you feel it is appropriate.

Here are the requirements that every class in your hierarchy needs to meet (except for the Runner class):
- At least one unique instance variable (unique from the superclass if relevant)
- A minimum of two constructors
    - One default constructor
    - At least one non-default constructor
    - Constructors have correct super calls when relevant
- Accessor/modifier methods for all instance variables in the class
- At least two method (that are not accessor/modifier methods) that do something particular to the class
    - At least one of these methods should have a non-void return type
    - If this class is a subclass, it should override at least one method of its superclass (though it can contain a call to the superclass’ method)
- Methods related to Polymorphism of any subclasses
    - These should not be accessor/modifier methods, and instead should be the more unique methods from subclasses
- Appropriate comments to describe the functionality of the class

Requirements for the Runner Class:
- A main/runner method that effectively tests each hierarchy class:
    - Tests all constructors
    - Tests all methods
    - Tests some Polymorphism combinations
    - Comments describing the expected behavior of test code
