# Class 10 notes

## error

What is a ‘call’?

The call stack is primarily used for function invocation (call). Since the call stack is single, function(s) execution, is done, one at a time, from top to bottom. It means the call stack is synchronous.

How many ‘calls’ can happen at once?

 The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error.

What does LIFO mean?

LIFO: When we say that the call stack, operates by the data structure principle of Last In, First Out, it means that the last function that gets pushed into the stack is the first to be pop out, when the function returns.

Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.
What causes a Stack Overflow?


A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. 

## JS Call Stack

What is a ‘reference error’?

This is as simple as when you try to use a variable that is not yet declared you get this type os errors.

What is a ‘syntax error’?

I know it’s in the name of the error, but like it says itself, this occurs when you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using JSON.parse.

What is a ‘range error’?

Try to manipulate an object with some kind of length and give it an invalid length and this kind of errors will show up.


[JS Call stack](https://www.freecodecamp.org/news/understanding-the-javascript-call-stack-861e41ae61d4)
[js error messages](https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c)
[JS Error reference](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors)