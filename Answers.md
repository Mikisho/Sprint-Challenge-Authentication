<!-- Answers to the Short Answer Essay Questions go here -->
1. 
* **Middleware**: are functions that performs tasks like excuting any code, changing resquest and response objects, ending req-res cycle and calling the next function in the stack.
* **Session**: is an interaction between two end points. In express, session data is stored at the server side. An express-session module is the one that provides an API to work with sessions with lets us to get and set data to the session.
* **bcrypt**: is a default passowrd hashing function algorithm which introduces a security factors that allows us to determine how expensive the hash function will be.
* **JWT**: is a middleware that validate JsonWebTokens and typically used in API endpoint protection.It is a way for securely transmit information between parties as a JSON object.
2. 
* **Bcrypt**: it excutees the hash function many times in a loop which makes it slow enough and becomes less feasible to be excuted against. 
3. 
* The three parts of **JWT** are:
    * Header
    * Payload
    * Signature
