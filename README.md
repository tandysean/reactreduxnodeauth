# CLIENT SERVER WITH AUTHENTICATION
React/redux front end with react router and browser history.
Persistent MongoDB server authentication service.

### Getting Started###
This project contains a few different components.
Front end is React/Redux app including react-router, and it's own packages.

#### React/Redux front end

Install dependencies and run the front end app on ```localhost:8080```.
 From the project root run:
<pre>
	> npm install>
	> npm start
</pre>

#### Node Authentication server
Make sure you have MongoDB installed.
Run mongo:
<code>
	> mongod
</code>

The node authentication server is it's own project. Provides api to front end app for authentication. Install dependencies and run for development
<code>
	> npm install
	> nodemon
</code>

Nodeman will auto-refresh changes to server, Webpack will live refresh the front end whenever you make changes. Unit tests have not been implemented, but ```mocha/chai``` test suite is ready to go.
