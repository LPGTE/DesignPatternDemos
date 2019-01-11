# DesignPatternDemos	

Design Pattern is a method of modeling computer software development solutions, it is used to organize the classes used in the source codes in order to allow the re-use of the developed solutions and the simplicity of the modifications of the needs during the phases of developments. In this follows, a scintetic presentation for the majority of patterns used in the development of computer software.

Behavior pattern :Behavior patterns are usually concerned for communication between objects.

State Pattern: It allows to create objects that represent several states, the object changes its state according to the methods applauded
Pattern command: The query is encapsulated in an object as a command and passed to an object sender, the emitter identifies the appropriate object for the command and passes this command to execute it.
Strategy Pattern: It defines and encapsulates a family of alghoprtithms, which allows the selection of alghorithm varies independently of client.The program selects one of these alghorithms based on the class Context. It is a pattern that changes during the run time. It is used for example in the case of Swtich Case where the switches are replaced by class processing.
Observe Pattern: It allows a part of the system to know when an event has taken place, if an object changes state the other dependent objects will be automatically notified.


Creation pattern: The pattern of creation concerns the creation of the objects, they hide the information of creation of the objects.

Factory Pattern: The factory pattern is one of the most used Design Patterns, it allows the creation of an object without the display of the creation logic to the client based on a common interface.
Abstruct Factory Pattern: It allows to provide an interface to create objects of the same family without specifying their concrete classes. the objects are grouped together as a family, the system must use the objects of a family or other. Typically used in the creation of libraries to encapsulate program methods through the provision of interfaces to client programs.
Builder Editor: It is used to create a complex object using simple objects and based on the step-by-step approach.
Singleton Pattern This pattern ensures that there is a class instance that will be accessible through a global access point.


Structure pattern: It describes how classes and objects are combined to form a large structure.

Facade Pattern: It hides system complexity and provides an interface for the client to access the system.
Adapter Pattern: It plays the role of an intermediary between incompatible interfaces.
Bridge Pattern: The bridge is used to decouple an abstraction from its implementation so that both vary independently
Decorator Pattern (Decorator or Wrapper): It allows to add new features for an existing object without modifying its structure
Proxy Pattern: The Proxy pattern has a feature for another class, creating an object to play the interface of another object.
Composite Pattern: The composite pattern is a collection of objects where each object can be a component or a simple compound object, it allows the client application to process Component and Compound objects in the same way.

MVC pattern: The Mvc pattern is used to separate the components of the application.

In the link following an implementation in C # for the majority of the patterns used, the examples are based on the courses presented on Tutorialpoint site, the classes used have been modified to bring the implemented patterns closer to the problems frequently encountered during the development phases of the tutorials. computer software in particular those which concern the beds of connections to databases.
