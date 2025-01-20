[[!2.5 Object Oriented Languages]]

Fundamental Theories

- **Encapsulation**: The bundling of data (attributes) and methods (functions) within a class, controlling access to them to ensure data security and integrity.
- **Polymorphism**: The ability of different objects to be treated as instances of the same class through shared methods, allowing for flexible and reusable code.

Key Examples

|Concept|Example|
|---|---|
|Class|`class Car { ... }` - Defines a blueprint for creating car objects.|
|Object|`Car myCar = new Car();` - Creates an instance of the Car class.|
|Method|`void startEngine() { ... }` - Defines a behavior for car objects.|
|Attribute|`String manufacturer;` - A property of the Car class.|
|Inheritance|`class SportsCar extends Car { ... }` - SportsCar inherits from Car.|

Key Principles

- **Instantiation**: The process of creating an object from a class.
- **Access Modifiers**: Keywords (public, private) that define the accessibility of classes, methods, and attributes.

Key Programming Languages

- **Java**: A widely-used object-oriented programming language that supports classes, objects, inheritance, and encapsulation.
- **C++**: Another object-oriented language that allows for complex data structures and polymorphism.

Facts to Memorise

- Class: A blueprint for creating objects in OOP.
- Object: An instance of a class with its own state and behaviour's.
- Method: A function associated with a class or object that defines behaviour.
- Inheritance: Allows a class to inherit properties and behaviours from another class.
- Encapsulation: Bundling data and methods within a class to protect the data.
- Polymorphism: The ability of different classes to be treated as instances of the same class through a common interface.

Reference Information

- Constructor: A special method called when an object is instantiated.
- Instance Variable: Attributes specific to an object created from a class.
- Class Variable: Attributes shared among all instances of a class.
- Access Modifiers: Keywords (public, private) that control access to class members.

Problem-Solving Steps

To create an object from a class:

1. Identify the class you want to instantiate.
2. Use the `new` keyword followed by the class name and parentheses.
3. Pass any required parameters to the constructor if necessary.
4. Assign the created object to a variable for further use.

**Common Pitfalls:**

- Forgetting to use the `new` keyword.
- Not matching the constructor parameters with the class definition.

Key Terms/Concepts

- **Class**: A blueprint or template for creating objects, defining their attributes and methods.
- **Object**: An instance of a class that has its own state and behaviours.
- **Method**: A function associated with a class or object that defines its behaviour.
- **Attribute**: A property or data member associated with a class or object that defines its state.
- **Inheritance**: A mechanism where a class can inherit properties and behaviours from another class, promoting code reuse.