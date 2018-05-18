<!-- Answers to the Short Answer Essay Questions go here -->

1.  Describe Middleware, Sessions (as we know them in express), bcrypt and JWT.

Sessions let the server store data about the client and are able to be accessed across requests.

Bcrypt is used for password encryption. It helps protect from brute-force and rainbow table attacks by slowing down hackers based on the timing that we can apply.

JWT sends information in JSON format, and works across different languages (e.g., NodeJS, JavaScript, Python). They send a payload and signature. They work inside HTTP headers when authenticating an API.

2.  What does bcrypt do in order to prevent attacks?
 
 bcrypt delays the time in which a hacker can decrypt a password. It converts your password into random characters and doesn't allow the hacker to reverse engineer the password such as they can do if they got a hold of a token.

3.  What are the three parts of the JSON Web Token?

The header, payload, and signature.
