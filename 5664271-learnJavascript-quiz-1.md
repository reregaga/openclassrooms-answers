[Quiz](https://openclassrooms.com/en/courses/5664271-learn-programming-with-javascript/exercises/3351)
# Check what you've learned about data and data types!

## Question 1
**Which of the following is a valid variable declaration and initialization?**
- [ ] let my variable = 12;
- [x] let myVariable = 12;
- [ ] variable myVariable = 12;
- [ ] let 12 = myVariable;

_A valid variable declaration and initialization needs the keyword  let, the name of the variable (in one word), the assignment operator  =, the desired value for the variable, and a semicolon  ;, in that order._

## Question 2
**Which of the following are primitive types in JavaScript?**
- [x] String
- [ ] Array
- [x] Number
- [x] Boolean
- [ ] Object
- [ ] Class

_The three most common primitive types in JavaScript are string, number, and boolean. Object and array are complex, reference types, and class is not a type at all!_

## Question 3
**What is the expected value of the variable  numberOfCats at the end of this code snippet?
let numberOfCats = 10;

numberOfCats += 5;
numberOfCats /= 3;
numberOfCats++;**
- [ ] 4
- [ ] 5
- [x] 6
- [ ] 7

_Initialize numberOfCats to the value 10. Then add 5 (15), divide by 3 (5), and use the  ++  operator to add 1, giving a final value of 6._

## Question 4
**Which of the following is true about constants?**
- [x] Once declared, their value cannot be changed.
- [ ] You can declare a constant without initializing it.
- [x] They help prevent mistakes or unexpected behavior.
- [ ] They can be converted from one type to another.

_Constants can help prevent mistakes and unexpected behavior in code, as they can never be accidentally changed. You cannot declare a constant without initializing it (as it always needs a value) and their type cannot be converted._

## Question 5
**In JavaScript, an object is declared as a series of comma-separated key/value pairs between…**
- [x] {}  Curly braces
- [ ] []  Square brackets
- [ ] ()  Parentheses
- [ ] None of the above

_Objects are declared between curly braces:
let firstBook = {
    title: 'The Story of Tau',
    numberOfPages: 250
};_

## Question 6
**How would you access the  title property on this  book object?
let book = {
    title: 'The Story of Tau',
    numberOfPages: 250
};**
- [ ] let title = book[title];
- [ ] let title = book.get('title');
- [x] let title = book.title;
- [ ] let title = title.book;

_To access a property on an object in JavaScript, use dot  .  notation, with the syntax  Object.Property._

## Question 7
**Consider the following class:
class Movie {
    constructor(title, director, duration) {
        this.title = title;
        this.director = director;
        this.duration = duration;
    }
}

Which of the following solutions correctly creates a new instance of this class?**
- [ ] let firstMovie = Movie('The Story of Tau', 'Will Alexander', 90);
- [x] let firstMovie = new Movie('The Story of Tau', 'Will Alexander', 90);
- [ ] let firstMovie = class Movie('The Story of Tau', 'Will Alexander', 90);
- [ ] let firstMovie('The Story of Tau', 'Will Alexander', 90);

_To create a new instance of a class, use the new keyword._

## Question 8
**An array is declared as a comma-separated list of values surrounded by…**
- [ ] {}  Curly braces
- [x] []  Square brackets
- [ ] ()  Parentheses
- [ ] None of the above

_Arrays are declared between square brackets:
let guests = ['Sarah Kate', 'Audrey Simon', 'Will Alexander'];_

## Question 9
**How would you add a new guest to the end of the following array?
let guests = ['Sarah Kate', 'Audrey Simon', 'Will Alexander'];**
- [x] guests.push('Tau Perkington');
- [ ] guests.unshift('Tau Perkington');
- [ ] guests.add('Tau Perkington');
- [ ] guests.pop('Tau Perkington');

_The  push() method adds an element to the end of an array. The  unshift() method adds the element to the beginning of an array. The  pop() method removes the last element of an array, and  add() method doesn't exist._

## Question 10
**How would you calculate how many elements there are in an array called  onlineUsers?**
- [ ] let numberOfUsers = onlineUsers.size;
- [ ] let numberOfUsers = onlineUsers.quantity;
- [ ] let numberOfUsers = onlineUsers.index;
- [x] let numberOfUsers = onlineUsers.length;

_The  length property tells you how many elements there are in that array._