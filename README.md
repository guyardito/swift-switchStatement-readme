# Switch Statements

![Adventure Time](http://i.giphy.com/FVbsOFYqdARtS.gif)


## Learning Objectives - The student should be able to..

* Explain that a switch statement considers a value and compares it against several possible matching patterns. It will execute an appropriate block of code, based on the **first** pattern that matches successfully. 
* Explain that a switch statement provides an alternative to the if statement which they had just learned to use.
* Understands that each case is a separate branch of code execution.
* Understands that every switch statement **must** be exhaustive. This means that every possible value of the type being considered must be matched by one of the switch cases.
* Explain that it's not practical to write **all** posible cases, where they could provide a default case to match all other possibilities as a catch-all. 



## What the student can do at this point 

* Create variables and constants
* Is familiar with type annotations, type inference and string interpolation.
* Can create functions with return types.
* Is familiar with the String, Int, Double and Bool type.
* Work with `if` and `else clauses`. 


## Outline / Notes

*  The student would have just come off reading about conditionals and doing a lab in Playground with it.
* Draw the connection between what they know about if statements to talk about switch cases.
* An example:

```swift
let color = "yellow"

switch color {
    
case "red":
    print("Red can cause failure on exams.")
case "orange":
    print("Orange is the only color of the spectrum whose name was taken from an object.")
case "yellow":
    print("In Japan, yellow is the color of courage.")
case "green":
    print("Before the 1950's Santa's suit was originally green until Coca-Cola bought him out and changed his suit to red.")
default:
    print("Your color isn't red, orange, yellow or green... therefore it's boring.")
    
}
```

```swift
if color == "red" {
    // red fact
} else if color == "orange" {
    // orange fact
} else if color == "yellow" {
    // yellow fact
} else if color == "green" {
    // green fact
} else {
    // no fact
}
```
* I'm thinking about **not** talking about *no implicit fallthrough* unless you disagree.
* I don't want to talk about interval matching as it might be throwing too much at them at this stage.
* Where switching on tuples is useful, the student doesn't know about Tuples (yet) and we can talk about switching on tuple types when we talk about tuples (in a future reading).

<a href='https://learn.co/lessons/SwitchStatement' data-visibility='hidden'>View this lesson on Learn.co</a>
