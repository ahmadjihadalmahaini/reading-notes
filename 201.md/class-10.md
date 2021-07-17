# read10
# Debugging and Error Handling
# ![](https://images.slideplayer.com/31/9700382/slides/slide_2.jpg)
##  Gracefully Handling No JavaScript Support
## Problem
## You want to ensure your pages work as well with JavaScript turned off as when it’s turned on.

## Solution
## One approach is to the use the noscript element to provide alternative functionality:
## script type="text/javascript"
## document.writeln("p" Some content"/p");
## "script"
## noscript"p" Fall back account"/p"/noscript
## Errors During Compiling
## A Script Error occurs when your script cannot be compiled because of a syntax error. This is flagged up in the script editor when you attempt to compile a change to a script by pressing the Apply button in the Code Editor. Correct the error then press the Apply button to compile the script again.
# ![](https://www.oreilly.com/library/view/javascript-and-jquery/9781118531648/images/p452-001.jpg)
## Caution: If a compile error is generated then the entire script to which it applies will not be compiled, not just the line or handler that contains the error. If other scripts are attempting to call commands or functions in this script they will not be able to run until you correct the problem and compile the script again.
## Because LiveCode compiles all the scripts within a stack when it loads them, a Script Error dialog can be generated when you load a stack from disk for the first time – if you saved a stack that contained a script that could not compile.
## Important: Do not confuse the Execution Error and Script Error dialogs. The Execution Error dialog occurs when a script is running and cannot continue due to an error. The error dialog will start with the words "executing at [time]". The Script Error dialog appears when you attempt to compile a script that contains a syntax error. The error dialog will start with the words "executing at [time]".
## Tip: If you turn on the Variable Checking option in the Code Editor, LiveCode will require that you declare all variables and enclose all literal strings in quotes. It will report a script compile error if you attempt to use an unquoted literal or do not declare a variable. This can be useful in catching mistakes before you run a script. Note that if you turn this option on and attempt to compile an existing script that has not been written in this way, it will typically generate a large number of errors that need to be corrected before you can compile it.
## Suppressing Errors and Messages
## If your stack gets into an unstable state where it is generating a large number of errors, you may want to temporarily turn off sending messages to the stack or displaying error messages. This can enable you to edit the stack to make the appropriate changes.

## To suppress messages, press the Messages button on the toolbar or choose Suppress Messages from the Development menu. Normal system event messages will stop being sent to the stack (for example clicking a button will no longer trigger a mouseUp handler, changing card will no longer trigger an openCard handler). You can still send custom messages directly to objects within the stack.
# ![](https://wordpress.org/support/files/2020/07/chrome-devtools.png)

## To suppress errors, press the Errors button on the toolbar or choose Suppress Errors from the Development menu. This will prevent any errors from triggering an error display window.
## Caution: Be sure to turn messages and errors back on when you have finished editing. Otherwise your stack will not work, or any error that comes up during stack operation will cause execution to halt but will not display an error message.
## You can execute a single navigation command in the message box with a similar effect as Suppress Messages by including the statement lock messages; before it. For example, to go to the next card lock messages; go next or to exit LiveCode (without displaying triggering any close messages or asking to save changes) lock messages; quit.


## Outputting information as your script executes
## If you want to know about the state of a particular variable or condition during execution, you can use the Variable Watcher, detailed below. However sometimes you may want to run a script without opening the debugger, outputting information along the way. You can use the put command to output information to the Message Box, a field or a text file, the write command to output to the Console, or the answer command to display a dialog.
## 