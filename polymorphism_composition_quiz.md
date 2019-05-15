# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?

Poly means many. Morph means to change shape. Polymorphism is being able to change into many shapes.

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.

Polymorphism is when we treat an object of one class as if it of another class or type at the same time.
If Car inherits from Vehicle then the variable Vehicle vehicle could hold an instance of Car.


3. What can we use to implement polymorphism in Java?

We can use an abstract class as a superclass or we can use interfaces. A class can only have one superclass but can have many interfaces.


4. How many 'forms' can an object take when using polymorphism?
It can take the form of its own class, any superclass above it in a chain of inheritance, although it can only inherit directly from one class, or any of its interfaces or those of the superclasses about it in the chain of inheritance.

5. Give an example of when you could use polymorphism.

i.e. when modelling a shop, it can hold an array of things which are IForSale as the shop does not require any other methods than those which apply to selling an item, so the stock could store any object which is IForSale, i.e. Food or TShirt.
when the items are sold, the customers can use them as the class they are i.e. eat something which is Food or wear something which is TShirt.

# Composition

6. What do we mean by 'composition' in reference to object-oriented programming?

Composition is when an object is made up of other objects or holds them.

7. When would you use composition? Provide a simple example in Java.

To build an Archer you would need a Bow, Arrows, and a Person.
A Bow in turn might be composed of a String and BowLimbs.

8. What is/are the advantage(s) of using composition?

It avoids complicated inheritance and inappropriate inheritance by building a class out of other classes which provide the behaviour we need.

9. When an object is destroyed, what happens to all the objects it is composed of?

The object owns the items it is composed of so when it is destroyed they are too.
