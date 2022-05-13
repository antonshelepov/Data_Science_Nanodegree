## OOP
### Why Object-oriented Programming?
Object-oriented programming has a few benefits over procedural programming, which is the programming style you most likely first learned. As you'll see in this lesson:
* Object-oriented programming allows you to create large, modular programs that can easily expand over time.
* Object-oriented programs hide the implementation from the end user.
![oop](screenshots/oop_1.png "object-oriented programming")
### OOP Vocabulary
* *Class*: A blueprint consisting of methods and attributes
* *Object*: An instance of a class. It can help to think of objects as something in the real world like a yellow pencil, a small dog, or a blue shirt. However, as you'll see later in the lesson, objects can be more abstract
* *Attribute*: A descriptor or characteristic. Examples would be color, length, size, etc. These attributes can take on specific values like blue, 3 inches, large, etc.
* *Method*: An action that a class or object could take
* *OOP*: A commonly used abbreviation for object-oriented programming
* *Encapsulation*: One of the fundamental ideas behind object-oriented programming is called encapsulation. You can combine functions and data all into a single entity. In object-oriented programming, this single entity is called a class. Encapsulation allows you to hide implementation details, much like how the scikit-learn package hides the implementation of machine learning algorithms 
![oop](screenshots/oop_2.png "oop 2")
### Difference between a method and a function
A function and a method look very similar. They both use the def keyword. They also have inputs and return outputs. The difference is that a method is inside of a class whereas a function is outside of a class.
### What is ```self```?
It is used in order to differentiate between two or more objects that are initiated by the same class.
```
shirt_one = Shirt('red', 'S', 'short-sleeve', 15)
shirt_two = Shirt('yellow', 'M', 'long-sleeve', 20)
```
## Notes about OOP
### Set and get methods
Benefits of ```set``` and ```get``` methods is that you can hide the implementation from your user. For example, originally, a variable was coded as a list and later became a dictionary. With the above mentioned methods you could easily change how that variable gets accessed.
[Python Tutorial site](https://python-course.eu/oop/properties-vs-getters-and-setters.php)
## A Gaussian class
### Important Defs and Formular
**Gaussian distribution formular**
probability density function
**Binomial distribution formulas**
mean
variance
standard deviation
probability density function
