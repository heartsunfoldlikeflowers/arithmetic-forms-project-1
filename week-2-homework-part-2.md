# Describe what the id attribute is.
The id attribute specifies a unique id for an HTML element

# What is the id attribute most used for? Name two uses.
to identify the element when linking, scripting, or styling.
it can be used to point to a specific declaration in the style sheet and also used to manipulate the DOM

# Should an id be unique within a page?
Yes

# Which built-in Javascript method do you use in your arithmetic project code to retrieve an element's id? Please name the method and describe what it does.
getElementById(). it returns an Element object representing the element whose id property matches the specified string

# If more than one element with the specified id does happen to exist, what does document.getElementById() return?
the first element in the code

# If no element with the specified id passed to document.getElementById() exists, what does document.getElementById() return?
null

# What is .value and why do we use it in our arithmetic functions?
. value sets or returns the value of the value attribute of a text field

# Describe the difference between a referenced function and an invoked (aka called) function. Please provide a code example for both a referenced function and an invoked function. Please provide examples of each using code from the Arithmetic Forms Project 1.
When you reference a function you are doing exactly that and not actually calling it
When you invoke a function, you are letting something run it

# Describe what the parseInt() method is, what it does, and why we use it in our arithmetic forms project. Include its syntax and parameters, and provide a code example from your project code using the function expression where it is implemented.
parseInt() parses a string which contains a number and returns an integer with a specified radix
parseInt(string, radix)  , string: value to parse & radix: optional.
let sum = parseInt(num1, 10) + parseInt(num2, 10);


# variable naming: Go into Mathias Byen's blog post entitled Valid JavaScript variable names in ES2015, and down to his variable name validator tool. Test 3 variable names you think up and check whether they are valid or not using the validator. Describe the 3 variable names that you checked in the variable name validator, whether they passed or not, and if not, why not.


# Declare and initialize a variable with var. Then re-assign the variable to another value.
var car = 1;
var car1 = 2;

# Describe the outcome, what it was, and why. Make sure to console.log() everything you want to have printed to the Developer Tools Console. Copy and paste the results from the Developer Tools Console into your .md file to show the outcomes. Whatever youconsole.log() inside your JavaScript code will show up in the Chrome Developer Tools Console. console.logging will also help you to better describe the outcome.

# Declare and initialize a variable with let. Then re-assign the variable to another value.

# Describe the outcome, what it was, and why. Make sure to console.log() everything you want to have printed to the Developer Tools Console. Copy and paste the results from the Developer Tools Console into your .md file to show the outcomes. Whatever you console.log() inside your JavaScript code will show up in the Chrome Developer Tools Console. console.logging will also help you to better describe the outcome.

Declare and initialize a variable with const. Then re-assign the variable to another value.
Describe the outcome, what it was, and why. Make sure to console.log() everything you want to have printed to the Developer Tools Console. Copy and paste the results from the Developer Tools Console into your .md file to show the outcomes. Whatever youconsole.log() inside your JavaScript code will show up in the Chrome Developer Tools Console. console.logging will also help you to better describe the outcome.

Describe what it means for a var variable to have global scope. Please provide an example.

Describe what it means for a var variable to have local scope. Please provide a code example.

Describe what it means for a let or const variable to have global scope. Please provide a code example.

Describe what it means for a let or const variable to have block scope. Please provide a code example.

Describe what lexical scope means. And what does it mean in the context of let or const variables? Please provide a code example.

Why do you think it would be preferable (when possible) for a variable to be declared and initialized in the local (or block) scope instead of the global scope?

What do Mathias Byens and Wes Bos (and I) think about using var with Modern JavaScript (ES6 and beyond)? Please explain their reasoning. And is there a right or wrong choice to make between var vs let and const? Refer to Wes Bos' post s var Dead? What should I use? as a reference.

Take your arithmetic addition form and describe to me what your JavaScript code is doing and what each part is called. For instance, are you using a named function, arrow function, or anonymous function? Are you using a built-in property of Document? Etc. Then describe what these parts do in relation to the DOM (your html markup), and in relation to css selectors, if applicable. Remember, there is a relationship between HTML, CSS, AND JavaScript. Break it down, step by step.