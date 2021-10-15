# Week 1 HW pt 2

# What is JavaScript?
*Javascript is a scripting or programming language that allows you to implement complex features on a web page letting the user interact with the DOM.*

# What can you use JavaScript for? Provide 4 examples of what JavaScript can do for you dynamically.
*You can use Javascript to create interactive features such as a button animation with difference responses, interactive map with location capabilities, animated graphics or images, and content that can constantly update like a clock or counter among other things.*

# What does DOM stand for?
*Document Object Model*

# What is ECMAScript?
*ECMAScript is a programming language, essentially the original form of Javascript when it was created and presented to ECMA international. ECMAScript is the standard that Javascript was built on and has since evolved from.*

# How are single line comments created in a JavaScript file? Please provide an example.
*Single line comments are created with two forward slashes. // This is an example*

# How are multi-line comments created in a JavaScript file? Please provide an example.
*Multi line comments are encased at the start by /* and concluded by */.*
/* This is a multi -
line example */

# What method prints out a message to the Browser Console? Please provide a code example and a single line comment above the code example. Please also include what is returned in the console in your answer along with your code snippet.
*The console. log() method outputs a message to the web console.*
// Homework Week 1 will appear in the brower console
<script> console.log("Homework Week 1"); </script>

# What is the definition of arithmetic operators?
*Arithmetic Operators take numerical values (either literals or variables) as their operands and return a single numerical value.*

# What is a numerical value literal?
*A numerical value literal refers to an actual number/integer.*

# What is a numerical value variable?
*A numerical value variable refers to a number/integer that has been stored as a value of a variable.*


# Which arithmetic operators does JavaScript support? List the arithmetic operators including their symbol, and please explain what each operator does.
_+ for addition - adds_
_- for subtraction - subtracts_
_* for multiplication - multiplies_
_/ for division - divides_
_% for modulo - returns remainder from division_

# How many types of numbers are there in JavaScript? And how can they be written?
*JavaScript has two types of numbers. Double precision floating point and BigInt.*

# What does BigInt make it possible to do when performing integer arithmetic?
*BigInt makes it possible to correctly perform integer arithmetic without overflowing*

# What is integer overflow, and why does it occur?
*Integer overflow occurs when an arithmetic operation attempts to create a numeric value that is outside of the range that can be represented with a given number of digits either higher than the maximum or lower than the minimum representable value*

# What is a double precision floating point number?
*Double Precision floating number is a format that stores numbers in 64 bits and where a fraction is stored in bits 0 to 51, an exponent in bits 52 to 62, and a sign in bit 63. Also regular numbers within safe range.*

# What is the sign of a number (referred to in the previous question)? And what built-in JavaScript method is used to find the sign of a number and how does it demonstrate this?
 + or - 
Math.sign()

# What is an integer?
*Numbers that don't have decimals or fractions*

# What is an operand?
*A value involved in an operation*

# What are the differences between the toFixed() method and the toPrecision() method?
*toFixed() - is used to constrain the number of decimal places shown*
*toPrecision() -  converts the number into a string, keeping the total number of digits of the value as specified and rounding them to the nearest decimal place*

# What is operator precedence? Please provide an example with the solution to the calculation.
*Operator Precedence determines how operators are parsed in relation to each other. The operands of operators with higher precedence are calculated before the operands of operators with lower precedence.*

# Consider the following arithmetic expression:

# console.log(10 + 6 * 8 - 5)
# What is the result of this arithmetic calculation? Please explain how you calculated this arithmetic expression using operator precedence.
*53 You start by multiplying 6 by 8 and then add 10 and subtract 5.*

# Consider the following arithmetic expression:
# console.log(10 + 6 * (8 - 5))
# What is the result of this arithmetic calculation? Please explain how you calculated this arithmetic expression using operator precedence.
*28 You start with the subtraction inside the double parenthesis then multiply by 6 and add 10.*

# Consider the following arithmetic expression:
# console.log(20 - (10 / 2) * 3)
# What is the result of this arithmetic calculation? Please explain how you calculated this arithmetic expression using operator precedence.
*-5 You start with the division inside the double parenthesis then multiply by 3 and subtract 20.*

# Consider the following arithmetic expression:
# console.log(30 + (20 / 5) * 6)
# What is the result of this arithmetic calculation? Please explain how you calculated this arithmetic expression using operator precedence.
*54 You start by dividing 20 by 5 then multiply by 6 and add 30.*