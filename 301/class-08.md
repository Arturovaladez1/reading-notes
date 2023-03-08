# Class 8 notes

## API Design Best Practices
What does REST stand for?

Representational State Transfer

REST APIs are designed around a ____.

REST is an architectural style for building distributed systems based on hypermedia. REST is independent of any underlying protocol and is not necessarily tied to HTTP. 

What is an identifier of a resource? Give an example.

A resource has an identifier, which is a URI that uniquely identifies that resource.

What are the most common HTTP verbs?

The most common operations are GET, POST, PUT, PATCH, and DELETE.

What should the URIs be based on?

esource URIs should be based on nouns (the resource) and not verbs (the operations on the resource).

Give an example of a good URI.



What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

Another factor is that all web requests impose a load on the web server. The more requests, the bigger the load. Therefore, try to avoid "chatty" web APIs that expose a large number of small resources. Such an API may require a client application to send multiple requests to find all of the data that it requires.

What status code does a successful GET request return?

retrieves a representation of the resource at the specified URI. The body of the response message contains the details of the requested resource.A successful GET method typically returns HTTP status code 200 (OK). If the resource cannot be found, the method should return 404 (Not Found).

What status code does an unsuccessful GET request return?

cannot be found, the method should return 404 (Not Found).

What status code does a successful POST request return?

If a POST method creates a new resource, it returns HTTP status code 201 (Created).

What status code does a successful DELETE request return?

respond with HTTP status code 204 (No Content)

## Sources

[REST](https://learn.microsoft.com/en-us/azure/architecture/best-practices/api-design)
[RegExr](https://regexr.com/)
[RegEx](https://medium.com/factory-mind/regex-tutorial-a-simple-cheatsheet-by-examples-649dc1c3f285)
[Regex](https://regex101.com/)
