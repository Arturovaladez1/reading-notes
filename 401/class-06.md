# Class 6 Notes

## Securing passwords

- Explain to a non-technical friend how you would safely hash and store a password.

Hashing will turn a password into something that is not a password, so when a hacker hacks the database, the passwords are still safe

- What is Bcrypt?

encryption algorithm for passwords

- Why might you use something like Bcrypt?

If you need to store passwords very securely and don't care about a higher impact to system resources.

## Basic Auth

- What is Basic Authentication?

A method for an HTTP user agent (e.g. a web browser) to provide a user name and password when making a request.

- What properties are necessary in the header of a Basic Auth request?

Credentials and a password are required.


- How are username:password in Basic Auth encoded?

Base64

## OWASP auth cheatsheet

- Define the authentication process to a non-technical recruiter.

 process of verifying that client, entity, or website is who they claim to be.

- How should your error messaging respond (both HTTP and HTML)? Why?

error messaging should return errors in a way that takes the same time for wrong usernames and passwords

## Sources

[Bcrypt Hashing](https://thehackernews.com/2014/04/securing-passwords-with-bcrypt-hashing.html)

[Basic Auth](https://en.wikipedia.org/wiki/Basic_access_authentication)

[Auth Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Authentication_Cheat_Sheet.html)

[bcrypt docs](https://www.npmjs.com/package/bcrypt)

