What do we mean by coupling and cohesion when discussing structured design?
These are two key concepts which measure the quality of software system's design.
coupling is the interdependence between software modules. High coupling is when the modules are close together and can affect each other.
Cohesion is how elements in a module work together for a purpose. High cohesion is when elements wihin a module are closely related and focused on a single purpose and low cohesion means elements in a module are loosely related and serve many purposes. 

What is the difference between top-down and bottom-up design? Which best describes a function oriented design?
Top-down design model is an overview of the system without the specific detail of it's subsystems. The subsystems are then refined in greater detail, breaking them down into different levels of subsystems. As they are boken into smaller parts, it helps us identify what needs to be built and allows more than one person to solve a problem. 
Bottom-up design model is when indiviudal parts of system are specified in detail. Once they are designed and developed, these parts/components are linked together to make a bigger component until the system is built. An advantage of this model is that decisons are made a low levels and the reuseability of components. An example of this is Java and C++ as each object is identified first. 

In which design methodology would a class diagram be most useful?
Top-down: Allows you to focus on the bigger picture and identify key classes and their relationships.
Bottom-up: Allows you to reuse components/classes for mantainable code and refine the diagram as you go along. 

What are the four pillars of object oriented programming? Give a single-sentence description of each.
Abstraction - Hide the implementation details which allows the essential part of code to be focused on. When you call a function, you do not need to understand what it is doing. Makes codebase easy to understand and reusable. 
Encapsulation - Removing access to some parts of code by making it private. Each object in code should control its own state. 
Inheritance - Creating new classes based on exisiting class. Subclasses inherit attributes and behaviour of parent class.
Polymorphism - A forn of abstraction that allows different classes to fulfill the same bhaviour.

What is the strategy pattern? How would its implementation differ between a functional and object oriented system?
The Strategy pattern works by seperating the behaviour of a object, from the actual object. The behaviour is encapsulated into different strategies and has its own implementation of bevaviour. The interaction happens through the same interface. 
In object orientated systems - strategy pattern is implemented through classes and interface. e.g Java
In functional system - strategy pattern is implemented using high-order functions / function references. e.g JavaScript 


Imagine your is creating a new online payment system. In order to gain maximum market share it can't be tied to a particular sector - it needs to work just as well when ordering a takeaway as when buying a new coat. Which design methodology would you suggest following? Give some justification for your decision.
Agile methodology??? - it priortises customers so can get feeback to diversify needs and make changes based their requirments through collaboration. This can be done through the sprint reviews, whereby stakeholders can express their needs. It is also flexible which is vital as the system needs to work accross various sectors. 