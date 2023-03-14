# Class 12 notes

## Status Codes Based On REST

In your own words, describe what each group of status code represents:

100’s =informational status codes

200’s = success codes

300’s = redirection codes

400’s =  client error codes

500’s = server error codes

What is a status code 202?

202 Accepted - Often used for asynchronous processing. This code tells the client that the request was valid, but its processing will finish sometime in the future

What is a status code 308?

308 Permanent Redirect - This tells the client to use another URL to access the resource and not use the current URL anymore. It’s helpful when we have multiple endpoints for one resource, but don’t want to implement reading from all of them.

What code would you use if an update didn’t return data to a client?

204 No content

What code would you use if a resource used to exist but no longer does?

410 Gone - This is like 404 but we know that the resource existed in the past, but it got deleted or somehow moved, and we don’t know where.

What is the ‘Forbidden’ status code?

The client has authorized or doesn’t need to authorize itself, but still has no permissions to access the resource.




[Status Codes](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)

[REST API](https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw)