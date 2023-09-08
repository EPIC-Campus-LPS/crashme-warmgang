# Lab 3: CrashMe

For this assignment, you and your partner will try and crash the included Java program in as many ways as possible. By editing lines of code and by using various inputs, you will document all of the different errors and exceptions you are able to cause at compile time and runtime. (This does not include syntax errors). Some errors you may try to cause are NullPointerExceptions, IndexOutOfBoundExceptions, StackOverflowErrors, etc. For some more inspiration here is a manual of errors and exceptions: https://drive.google.com/file/d/1skAJl91CHexfGpH3uN8893mp_DuXjLql/view?usp=sharing

## Pair Programming
To complete this assignment, we will use the pair programming model. One person will be the **Driver** and the other will be the **Navigator**. The Driver's responsibility is to write or edit the code/project. The Navigator's responsibility is to read the code as it is being typed, bring in outside resources, generate ideas, etc. Every 15-20 minutes, the two people will switch.  

At the end of the assignment, complete the following reflection about the pair programming model.
1. What was successful about the pair programming model for your group?
2. What changes would you make to this model to make it more successful for your group?
3. Why do you think software developers use this strategy when developing code?

## Documentation
Rather than submitting code for this assignment, you will edit and push this README.md file to document your progress.

For each exception and error you cause, report the following:
1. What exception or error did you cause?
2. How did you cause it?
3. What does that exception or error mean? Did it occur at compile time or runtime?

## Compile Time Errors
- "expected" error on line 27 after removing the ending parenthesis, meaning it expected the parenthesis to be there because of the starting parenthesis existing
- "unclosed string literal" error on line 30 after removing the closing quotation mark, meaning it expected the closing quotation mark to be there because of the opening quotation mark
- "illegal start of expression" error on line 8 after commenting out the variable content, meaning it has nothing to assign to the variable 
- "not a statement" error on line 10 after defining a variable without an assignment operator, meaning the computer was told something but not given specifics about it
- 

## Runtime Errors
- "ArrayIndexOutOfBoundsException" on line 14 after trying to access the 2000th index of an array that was specified with a length of 1; this means that the code tried to look at a value that doesn't exist
- "NullPointerException" on line 14 after trying to print a String that did not exist
- "StringIndexOutOfBoundsException" on line 68 after trying to access the 2000th character of a string of length 6; this means that the code tried to look at a part of the string that didn't exist
- "InputMismatchException" on line 8 after inputting a string when it expected a integer; this means that the computer was given a data type it couldn't do anything with
- "ArithmeticException" on line 30 after dividing by zero; the computer cannot handle indeterminate forms
- 