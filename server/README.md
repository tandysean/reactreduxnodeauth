# nodeAuthServer
A extensible node authentication service using JSON Web Tokens and BCRYPT that can easily be dropped into any node project. Very easily adaptable and very secure.

Requires you to create a config.js file at server root directory level which exports a secret key to Salt the encryption.
<pre>
module.exports = {
  secret: 'YOUR SECRET STRING'
};
</pre>

Uses ```nodemon``` for auto refresh and ```expressjs``` for API

Upon cloning use ```npm install``` to install dependencies and then start the server by running ```npm run dev```
