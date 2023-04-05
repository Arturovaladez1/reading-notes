# Class 03 notes

## Review: ES6 Classes

Classes are a template for creating ____.
Objects

Can a class declaration be hoisted?
no

How would you describe a constructor and contextual “this” to a non-technical friend?
A constructor is a function that is called when a new class is created. This new class will have access to the constructor prototype. You can reference it wth the this keyword

## Using Express Routing

Within Express, what does routing refer to?

How an application’s endpoints respond to client requests.

What is the difference between a route path and a route method?

Route method is the type of request made, while route path is the actual path to the endpoint to make the request.

When is it appropriate to add next as a parameter to a route handler and what must you do if next has 
been passed to your middleware as a parameter?

You can add next to a route handler if you want it to be able to bypass the remaining operations and be handed off to the next handler, or to chain callbacks. If next passed as a parameter to your middleware, you need to invoke next in order to pass the request on.

## Express Routing

What is an Express Router?

It is a mini express application without all the bells and whistles of an express application.

By what mean do we initialize express.Router() in an express server?

var router = express.Router();

What do we use route middleware for?

Route middleware is used to process requests and validate parameters passed in

