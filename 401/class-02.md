# Class 2 notes

## An introduction to NodeJS and Express

Explain middleware, answer as though I were a non-technical recruiter.

You can use Express middleware to add support for cookies, sessions, and users, getting POST/GET parameters, etc.

Express the most popular __ __ ____.

NODE WEB FRAMEWORK

Express is “unopinionated.” What does that mean?

Unopinionated frameworks, by contrast, have far fewer restrictions on the best way to glue components together to achieve a goal, or even what components should be used. They make it easier for developers to use the most suitable tools to complete a particular task, albeit at the cost that you need to find those components yourself.

You can insert almost any compatible middleware you like into the request handling chain, in almost any order you like. You can structure the app in one file or multiple files, and using any directory structure.

What is a module and why is modularity useful to us as developers?

A module is a JavaScript library/file that you can import into other code using Node's require() function. Express itself is a module, as are the middleware and database libraries that we use in our Express applications.

## What is NPM

What version of npm are you running on your machine?

9.6.0

## TDD

Explain why tests are important. Please explain as though I were your non technical elder.

significant reductions in defect rates, improved design qualities in the code, and more generally a higher degree of “internal” or technical quality, for instance improving the metrics of cohesion and coupling

What are three expected benefits of testing

productivity, code simplicicty and less work towards the finsihed product.

Name at lest 2 individual pitfalls and at least 2 team pitfalls commonly encountered while writing tests.
CI

forgetting to run tests frequently
writing too many tests at once

partial adoption – only a few developers on the team use TDD
poor maintenance of the test suite – most commonly leading to a test suite with a prohibitively long running time

## sources

[Express/Node Intro](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Introduction)

[npm](https://docs.npmjs.com/about-npm)

[test](https://www.agilealliance.org/glossary/tdd/#q=~(infinite~false~filters~(postType~(~'page~'post~'aa_book~'aa_event_session~'aa_experience_report~'aa_glossary~'aa_research_paper~'aa_video)~tags~(~'tdd))~searchTerm~'~sort~false~sortDirection~'asc~page~1))
