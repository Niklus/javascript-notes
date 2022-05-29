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

## Arrays

- array.length returns the number of elements inside the array.
- array.push(x) allows you to add the variable x to the end of the array.
- array.push(x) returns the new length of the array (after the push has been made).
- Arrays defined with const are not constants because you can change the elements inside of it. However, you cannot re-assign them to another value thus they will always be an array.
- .forEach(callback) iterates over every item in an array.
- A callback is a function definition passed as an argument to another function.
- The .forEach() method will take your function definition and call it for every item of the array. Every time it calls it, it will replace the first parameter with the corresponding array item.
- The .filter() method returns a new array that contains some of the items from the original array, based on the condition you specify.
- JavaScript will take your callback function and call it for every single item in the array.
- For the .filter() method, the result of the callback function matters. When it's true, the item will be included in the resulting array. Otherwise, it won't.
- The .find() method returns the first item which matches the condition that you specify. If no items were found, you will get back undefined.
- The array .map(callback) method allows you to transform an array into another one.
- The array .includes(item) method takes an item and returns true when that item exists in the array and false otherwise.
- The array .join(glue) method returns a string of the array elements separated by the glue.

## Objects

- An object is a data type that allows you to group several variables together into one variable that contains keys and values.
- It's recommended that you use camelCase for property names (for example firstName instead of first_name).
- To read or update the value of a property, you can use the dot notation.
