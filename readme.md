# JavaScript

## Strings

- You can create strings with " or ' or `
- .length is a property that gives you the length of a string
- .toUpperCase() is a function that converts the string to upper case
- .toLowerCase() is a function that converts the string to lower case
- parentheses () on function calls are required. .length is a property that is already pre-computed; therefore, it does not need parentheses.
- Square brackets with index are used to access a specific index from a string
- The index starts at 0. So the first character is index 0
- A substring is a part or a portion of a string.
- string.substring(indexStart, indexEnd) is used to return a portion of the string.
- indexStart: the position of the first character you'd like to include.
- indexEnd: the position of the first character you'd like to ignore.
- the indexEnd argument is optional which means you can leave it out.

## Template Strings

- A template string is a string created with the back-tick character: `
- Template strings can span multiple lines
- Template strings support interpolation with the ${variableName} syntax

## Numbers

- Convert from a number to string: value.toString()
- NaN stands for Not a Number
- NaN is often a sign of a bug.
- Convert from string to number Number.parseInt(value, 10).
- Number.parseInt() is the name of the function you're calling.
- 10 is the radix which you should specify.
- Make sure to always specify the radix to avoid unpleasant surprises.

## Variables

- When you use a variable for the first time in JavaScript, you need to declare it with either let or const.
- Use let for variables that you will need to re-assign later on (as in changing their value)
- Use const for variables that you won't need to re-assign later on.
- Variables declared with const are not constant. We will see why later in this course.
- Variables declared with const cannot be re-assigned so you cannot have the = next to that variable name after declaring it.
- If you see var, it's from the old version of JavaScript. You can convert it to let (sometimes const if the variable is not re-assigned).

## Conditions

- Using an if condition, you can run a piece of code when the condition evaluates to true
- The syntax is if (condition) and then curly braces {} wrap the lines of code that correspond to this condition
- The else keyword can be used to perform some other code based on all the other conditions not satisfied with the if.
- When you have an if/else condition that returns two different results, it is possible to drop the else keyword.
- Always use triple equals (===) when comparing 2 values in JavaScript.
