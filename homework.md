
# What does the word 'polymorphism' mean?

Polymorphism is the word used to describe the ability of a class or an object to perform a single task in different ways.

# What does it mean when we apply polymorphism to OO design? Give a simple Java example.

An object can have many characteristics and so can act differently according to the object with which it is interacting. For example, a person can be a software developer at work, a husband at home etc.

# What can we use to implement polymorphism in Java?

You can use abstract classes, static methods and interfaces to implement polymorphism.

# How many 'forms' can an object take when using polymorphism?

As many as you like.

# Give an example of when you could use polymorphism.

A Guitar Class could be a child of the abstract MusicalInstruments class. It could then take the method play() from MusicalInstruments but implement it in it's own way.

### Composition and Aggregation

# What do we mean by 'composition' in reference to object-oriented programming?

Composition is the way we refer to the 'has-a' relationship between two or more objects in a program.

# When would you use composition? Provide a simple example in Java.

We would use composition where an object makes use of another object but is not directly related to it. For example, a Driver could use a Truck, but neither is directly related to the other.

# Give a difference between composition and aggregation?

Aggregation is a weaker association between two or more objects than composition. Aggregation = loose coupling whereas composition = tight coupling.

# What is/are the advantage(s) of using composition/aggregation?

Composition and aggregation allow us to take advantage of the polymorphism inherent in Java.

# When using composition, when an object is destroyed, what happens to all the objects it is composed of?

As one class is dependent on another class in composition, the dependent class can not exist independently if it's dependee is destroyed.

# When using aggregation, when an object is destroyed, what happens to all the objects it is composed of?

They are chill.