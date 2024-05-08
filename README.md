# h1 Writing a Function in JavaScript

![coders coding](https://plus.unsplash.com/premium_photo-1682140993556-f263e434000b?w=800&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MXx8Y29kaW5nfGVufDB8fDB8fHww) 

In JavaScript, functions are blocks of reusable code. They allow you to bundle functionality, make it more readable, and avoid repetition. Here's a brief tutorial on writing an arrow function in JavaScript.

### 1. Basic syntax
```
const functionName = (params) => {
  // code to be executed
}
```
__const__: 
* const should be used whenever a function expression is assigned to a variable.
* The function name: The name you choose for the function.
* Parameters: Optional comma separated parameters. 
* This is the data passed into the function. If there are no parameters, the () is still required.
The arrow syntax: Indicates that this will be a function.
* The body: The statements that make up the function itself. Surrounded by curly braces.

***Example***:
```
const greet = (name) => {
  console.log("Hello, " + name + "!");
}
```
>__Tip__: Functions often perform actions, so naming with a verb can make it clear what the function does. Examples include fetchData( ), calculateArea( ), or printReport( ). 

### h3 2. Calling a function

To execute the function, you *call* or *invoke* it by using its name followed by parentheses.

***Example***:
```
greet('Alice'); // Outputs: Hello, Alice!
```
### h3 3. Return values

Functions can process data input and output a value using the *return* keyword.

***Example***: 
```
const addNums = (numA, numB) => {
  return numA + numB
}

const total = addNums(2, 4);

console.log(total) // Expected value: 6
```
For more information on functions and how they are used in JS, check out the MDN docs. 
[MDN Functions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions)

# h1
## h2
### h3
#### h4
##### h5
###### h6# h1

## h2 embolden by using
This text is **bold**. This text is also __bold__.

## h2 italicize by wrapping with
This text is in *italics*.This text is also in _italics_.

## h2 do both with
This text is ***bold and italicized***. This text is also ___bold and italicized___.

* Item 1
* Item 2
  * Subitem 2.1
  * Subitem 2.2
    * Subitem 2.2.1

1. First item
1. Second item
   1. Subitem 2.1
   2. Subitem 2.2

//to show code that is capable being copied
Use the `console.log()` function to print values to the console.

//for multi line
```javascript
const printItem = (item) => {
  console.log(item);
}
```
//add a link with this
[Google](https://www.google.com)

//to add a referance for a link do this
[this is the reference][example].

[example]: http://www.example.com/

> This is a blockquote. 
> First level of blockquote.
>> Nested blockquote.
>>> Another nested blockquote.
>>>>Blockquotes can contain other Markdown formatted elements, like headers, lists, or even other blockquotes. Try it out.

//Embedding images
![some alt text](www.url_to_an_image.com/image)


![Computer with Code](https://images.unsplash.com/photo-1587620962725-abab7fe55159?auto=format&fit=crop&q=80&w=1631&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D)


  

| Syntax | Description |
| ------ | ----------- |
| Header | Title |
| Paragraph | Text |

//task lists
- [x] Task 1
- [ ] Task 2
- [ ] Task 3
  
  This text has been ~~redacted~~. 

greet('Alice'); // Outputs: Hello, Alice!`
```
const addNums = (numA, numB) => {
  return numA + numB
}

const total = addNums(2, 4);

console.log(total) // Expected value: 6
```