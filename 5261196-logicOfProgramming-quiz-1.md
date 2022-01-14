[Quiz](https://openclassrooms.com/en/courses/5261196-think-like-a-computer-the-logic-of-programming/exercises/2640)
# Software objects 101

## Question 1
**Which of the following is true of objects in programming (3 correct answers)?**
- [x] They can be used to model real-world objects.
- [ ] They are not used to represent real-world objects; this is just an analogy to help us to talk about them.
- [x] They help programmers to group descriptions and details together.
- [x] They can also be called "instances of a class."

_Software objects are modeled off of real-world objects.  That's part of why they're so useful when designing computer systems for the real world!_

## Question 2
**Which of the following is true about attributes?**
- [x] Attributes describe what an object is composed of.
- [ ] Attributes are used to define security access.
- [ ] Attributes define what actions you can take with an object.
- [ ] Attributes cannot have values.

_Objects have a list of attributes that define what they're made up of.  This is not to be confused with methods, which define behaviors, or rather, what you can do with an object's attributes.  Security access is defined by the access control._

## Question 3
**Which of the following is true about methods? (2 correct answers)**
- [ ] Methods is another way of referring to famous rappers from the 90s.
- [x] Methods define what you can do with an object's attributes.
- [x] Methods refer to an object's behavior.
- [ ] Methods are what you use to plan out what's in your object.

_Methods have nothing to do with rap (obviously) and you plan our your object using a class._

## Question 4
**What do we mean by "access control" in programming?**
- [x] It specifies who has access to the methods in your object.
- [ ] It's a fancy security card with a barcode that you use to get into secure places, like the FBI building or the secret recipe room of a beverage company.
- [ ] It's an attribute of an object.
- [ ] It defines who can open your cellar door.

_In programming, access control only defines who can use your methods or the degree of access to them (private, public, etc.), not your object in general. Methods define what can be done with your attributes, not access control.  Answers 2 & 4 are good analogies, but not the actual definition of access control._

## Question 5
**Which of the following is true of the term "class" in programming? (2 correct answers)**
- [ ] In programming, "a class" is a synonym for "an object."
- [x] A class is a plan or blueprint for your object.
- [x] A class defines the attributes, methods, and access control for an object.
- [ ] Class is something all programmers have.
- [ ] Classes are constructed after you bring your object into being.

_Objects and classes aren't the same things, though they are connected. Classes are a plan for your object. Using this plan, you can bring an object into being. It doesn't really make sense to make an object first and the plan after. That'd be like building a house before you create a blueprint! Also, some programmers may be classy, but that's not really what's meant by "class" in programming._

## Question 6
**What is the programming term for "bring an object into being?"**
- [ ] Antidisestablishmentarianism
- [x] Instantiation
- [ ] Objectification
- [ ] Instance definition
- [ ] Object definition

_We instantiate an object when we want to bring it into being.  This is why an object can be referred to as "an instance of a class."_

## Question 7
**Can objects of the same class differ from one another?**
- [ ] Yes, because objects can contradict any of the requirements set out by their class.
- [x] Yes, different objects can have different values for their attributes.
- [ ] No, objects must be exact copies in order to follow the requirements set out by the class.
- [ ] No, if you want different types of the same object, you should make a different class for each one.

_Regardless of the type of object you're making, the values of an attribute can vary for each object - as long as they respect the guidelines set out by the class! Instances of a class are not exact copies.  This is part of why using objects is so useful!_

## Question 8
**Which of the following is true about complex systems?**
- [ ] An object cannot have another object as an attribute.
- [ ] Objects do not send messages to one another.
- [x] Objects can communicate with one another by sending messages.
- [ ] Objects are isolated and cannot be used in complex systems.

_Complex systems are networks of associated objects that communicate via messages.  Objects can have another object as an attribute._

## Question 9
**What is encapsulation?**
- [ ] It refers to hiding information in an object in order to simplify its use.
- [x] It's refers to bundling attributes, methods, and access control together in one unit.
- [ ] It when two objects interact within the same system.
- [ ] It's an eco-friendly version of an espresso pod.

_Encapsulation bundles together data and behaviors - like attributes, methods, and access control - but it doesn't necessarily hide this information._

## Question 10
**What is abstraction?**
- [ ] It allows us to bundle together information to simplify its utilization.
- [ ] It's a method of highlighting the complexity of a particular object, in order to ensure that it's used correctly.
- [ ] It's an art movement from the 20th century that has heavily influenced programmers.
- [x] It means only showing what's relevant or necessary for using an object.

_Abstraction means hiding the more complex mechanisms of an object in order to simplify use, leaving only what's relevant or useful available to the person using it.  The bundling together of information is referred to as encapsulation._