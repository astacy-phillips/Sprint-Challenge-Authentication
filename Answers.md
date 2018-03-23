<!-- Answers to the Short Answer Essay Questions go here -->

1.  Describe Middleware, Sessions (as we know them in express), bcrypt and JWT.
    - Middleware in express - functions that have access to req, res and next and are able to be used globally and locally.
    - Sessions - used to store and access data, generally user data as they interact with the app
    - bcrypt - a password hashing function
    - JWT - a way to send information between parties as a JSON object. Similar to cookies.

2.  What does bcrypt do in order to prevent attacks?
    - bcrypt adds a salt either before or after the password then hashes them together. 
3.  What are the three parts of the JSON Web Token?
    - Header, payload and signature
