[Quiz](https://openclassrooms.com/en/courses/5261196-think-like-a-computer-the-logic-of-programming/exercises/2729)
# Understand logic flow and decision making

## Question 1
**How do computers solve problems?**
- [ ] They guess what we want, and they find a solution.
- [x] They don't! We tell them exactly what to do.
- [ ] They receive an end goal and find a way to get there using logic.
- [ ] They do a lot of trial and error until they succeed.

## Question 2
**What is true about logic flow?**
- [x] It refers to the order in which a series of steps is completed in a program.
- [ ] Steps can be done simultaneously in a program.
- [x] Steps are done one after the other in a program.
- [x] Some steps can be done before or after other steps without affecting the logic of the program.

_The logic flow refers to how the steps in a set of instructions are executed - notably the order. Steps are sequential and can be independent but cannot be done simultaneously._

## Question 3
**What values can a Boolean have?**
- [x] True
- [ ] Null
- [ ] Empty
- [x] False
- [ ] Undefined

_Booleans have only values: true or false. Null and empty are other values not associated with Booleans._

## Question 4
**What is the difference between empty and null?**
- [x] Null means there is no value and there’s no indication that there will be one in the future.
- [ ] Null means there is no value currently, but the computer knows there will be one in the future.
- [ ] Empty means there is no value and there’s no indication that there will be one in the future.
- [x] Empty means there is no value currently, but the computer knows there will be one in the future.
- [ ] There isn't a fundamental difference; they are both used to represent the same thing in programming.

_The difference between empty and null is critical. It hinges on whether a value is planned for or not. With empty, the value isn't there, yet.  With null, there's no value and there's nothing indicating that it will be._

## Question 5
**Check out these instructions: The coffee is hot.  AND The coffee is strong.
In programming, what does the logical operator AND signify in the line above?**
- [ ] To be valid, either one of the statements can be true.
- [ ] To be valid, one of the statements must be true.
- [x] To be valid, both of the statements must be true.
- [ ] To be valid, neither one of the statements can be true.

_AND requires that both statements be true in order to consider the set of instructions to be true._

## Question 6
**Check out these instructions: The coffee is served with cream. OR The coffee is served with sugar. 
In programming, what does the logical operator OR signify in the line above?**
- [x] To be valid, both statements can be true (though this isn't required).
- [x] To be valid, at least one of the statements must be true.
- [ ] To be valid, only one of the statements can be true.
- [ ] To be valid, neither of the statements can be true.

_OR requires that at least one statement to be true in order to consider the set of instructions to be true._

## Question 7
**Check out these instructions:  The coffee is NOT ready. 
Which response would indicate that this statement is false, and the coffee is ready?**
- [ ] Null
- [x] NOT true
- [ ] NOT false
- [ ] Lies

_NOT true means true, which is the answer we're looking for.  NOT false means false. Null doesn't mean false and lies is not a valid value._

## Question 8
**How would you write the following as an if/else statement? OK, after this quiz, I'm going to the movies.  Unless I fail the quiz.  In that case, I'll study a bit more and retake it.**
- [ ] 
- [x] 
- [ ] 
- [ ] 

_Here, passing the quiz is the condition.  If passing the quiz is true, then you'll do action 1: going to the movies. If passing the quiz is false, you'll do action 2: study a bit more and retake it. This second action goes in the else part of the statement._

## Question 9
**What is true about greater than, less than, and equal to in programming?**
- [x] They are used to compare values.
- [x] They can be used in IF/ELSE statements.
- [ ] They cannot be used in IF/ELSE statements.
- [ ] They are leftovers from when computer programs only did math and are now obsolete.

_All three can be used in IF/ELSE statements, and they are most certainly used in programming today!_

## Question 10
**Which of the following statements accurately describes loops?**
- [ ] Loops are time-consuming to write and cost you more time than they save.
- [ ] Loops allow objects to send messages to one another.
- [x] Loops allow programs to repeat sets of instructions over and over again.
- [ ] Loops are only used in graphic design programs to help create animations.

_Loops are not designed for sending messages between objects and they are very helpful for saving you time when you're writing code. Loops are used everywhere in programming - not just in graphic design!_

## Question 11
**What is true about infinite loops?**
- [x] While loops can create infinite loops.
- [x] Infinite loops happen when a developer forgets to indicate an end condition within a loop.
- [ ] Infinite loops happen when a computer can't finish its pack of cookies.

_There's no danger of creating an infinite loop with a for loop, because it will only repeat a specific number of iterations and stop._