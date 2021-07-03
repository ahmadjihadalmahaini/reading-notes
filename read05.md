# read05

# Loops and iteration
## Loops offer a quick and easy way to do something repeatedly. This chapter of the JavaScript Guide introduces the different iteration statements available to JavaScript.

## You can think of a loop as a computerized version of the game where you tell someone to take X steps in one direction, then Y steps in another. For example, the idea "Go five steps to the east" could be expressed this way as a loop:
# ![image](https://docs.kumu.io/images/elements-connections-loops-bold.png)
## There are many different kinds of loops, but they all essentially do the same thing: they repeat an action some number of times. (Note that it's possible that number could be zero!)

# for statement
## A for loop repeats until a specified condition evaluates to false. The JavaScript for loop is similar to the Java and C for loop.

## A for statement looks as follows:

## for ([initialExpression]; [conditionExpression]; [incrementExpression])
# do...while statement
## The do...while statement repeats until a specified condition evaluates to false.

## A do...while statement looks as follows:
## do
  # statement
# while (condition);
## statement is always executed once before the condition is checked. (To execute multiple statements, use a block statement ({ ... }) to group those statements.)
# ![image](https://media.geeksforgeeks.org/wp-content/uploads/20191118164726/While-Loop-GeeksforGeeks.jpg)
# labeled statement
## A label provides a statement with an identifier that lets you refer to it elsewhere in your program. For example, you can use a label to identify a loop, and then use the break or continue statements to indicate whether a program should interrupt the loop or continue its execution.

## continue statement
# The continue statement can be used to restart a while, do-while, for, or label statement.

# When you use continue without a label, it terminates the current iteration of the innermost enclosing while, do-while, or for statement and continues execution of the loop with the next iteration. In contrast to the break statement, continue does not terminate the execution of the loop entirely. In a while loop, it jumps back to the condition. In a for loop, it jumps to the increment-expression.
# When you use continue with a label, it applies to the looping statement identified with that label.
# The syntax of the continue statement looks like the following:

