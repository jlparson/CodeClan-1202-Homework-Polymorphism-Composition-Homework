# CodeClan-1202-Homework-Polymorphism-Composition-Homework

**Polymorphism**

**1. What does the word 'polymorphism' mean?**

**Answer:** The condition of occurring in several different forms.

**2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.**

**Answer:** We apply polymorphism when we create objects which take on the attributes and methods of classes on their inheritance chain or interfaces they implement. For example, if we had a class of WashingMachine, it could have attributes or methods that are unique to it, but it could also use those from it's inheritance chain such as KitchenAppliance or Machine (i.e. Machine -> KitchenAppliance -> WashingMachine). It could also have attributes from an interface IClean. Therefore, WashingMachine is a washing machine, but it is also a KitchenAppliance and an IClean and a Machine.

**3. What can we use to implement polymorphism in Java?**

**Answer:** We can use inheritance, abstract classes and interfaces to implement polymorphism in Java.

**4. How many 'forms' can an object take when using polymorphism?**

**Answer:** An object can take the 'form' of any class in its inheritance chain, as well as any interfaces it implements.

**5. Give an example of when you could use polymorphism.**

**Answer:** We could have a superclass called Animal with a method animalSound(). Any subclasses that inherit from Animal can manipulate the method to make their own sound. A Cat subclass can 'meows', a Dog can 'barks' a Horse 'neighs', etc. A Cat is a cat, but it is also an Animal (as is Dog, Horse, etc.).

**Composition and Aggregation**

**6. What do we mean by 'composition' in reference to object-oriented programming?**

**Answer:** In OOP, composition is when a class is composed or made up of instances of another class. This means it uses instances of another class as properties.

**7. When would you use composition? Provide a simple example in Java.**

**Answer:** You would use composition when one object is made up of other objects. For example, if you had a class of HumanBody it would be composed of a Heart, Brain, Kidney, etc.

**8. Give a difference between composition and aggregation?**

**Answer:** A difference between composition and aggregation is that with aggregation, the objects it has can exist independently from the object that contains it. 

**9. What is/are the advantage(s) of using composition/aggregation?**

**Answer:** The advantages of using composition are that we can reuse code without having to rely on inheritance. Using inheritance only can be limiting because one class can only inherit from another class on their inheritance chain. Another advantage is that composition offers us good testability of a class.

**10. When using composition, when an object is destroyed, what happens to all the objects it is composed of?**

**Answer:** When the object is destroyed, all of the objects it is composed of cease to exist.

**11. When using aggregation, when an object is destroyed, what happens to all the objects it is composed of?**

**Answer:** When the object is destroyed, the objects it is composed of still exist independently from the object.
