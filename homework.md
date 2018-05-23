Polymorphism

1.	What does the word 'polymorphism' mean?
     It means many forms with poly' meaning 'many' and "morph" meaning 'change'.

2.	What does it mean when we apply polymorphism to OO design? Give a simple Java example.
     Polymorphism allows an instance of a class to be treated as if it is also another class/type at the same time.  For example in a home network of desktop, printer and monitor you could set up an interface to hold the connection method which the three components could implement, which means that, for example, the desktop is both a desktop and a connection.

3.	What can we use to implement polymorphism in Java?
     It can be implemented using abstract classes and interfaces.

4.	How many 'forms' can an object take when using polymorphism?
     It can take on many forms, no fixed number.

5.	Give an example of when you could use polymorphism.
   Carrying on from the example at point 2 above, if we wanted to know the connection status of all the devices mentioned on, say, a home network, once the interface has been set up and printer, desktop and monitor classes implement it, then in a network class an ArrayList of the interface connection can be created which means the ArrayList can contain the desktop, printer and monitor objects.

Composition

6.	What do we mean by 'composition' in reference to object-oriented programming?

     Composition in OOP is when an object is made up of, or composed of other objects.

7.	When would you use composition? Provide a simple example in Java.

     You would use composition when various class have different traits but are essential components of another class, for example a fuel tank and engine are unlikely to contain similar methods however both are vital components in a car. When considering the attributes for the car class you would include objects/classes which could be described as a 'HAS-A', ie a car has a fuel tank.

8.	What is/are the advantage(s) of using composition?
     Composition allows a class to use behaviour from a group of other classes.

     Composition has a higher degree of flexibility, compared to inheritance, because using interfaces means that the class only has to adopt the methods applicable to the interface whereas with inheritance it has to adopt everything it inherits. It is better to compose what an object can do (HAS-A) than extend what it is (IS-A).

     Composition make each class less prone to the quirks of other related classes as it avoids problems that can come with inheritance whereby a change to a class in an inheritance structure may impact several generations of classes.

9.	What happens to the behaviours when the object composed of them is destroyed?

     In composition, the object composed of other behaviours owns those behaviours. This means that when the object is destroyed all of its behaviours are also destroyed.
