# Common Errors

Below is a table of errors that web developers see frequently.  On the left is a part of the error text.
On the right is what the error is trying to tell us in English.


| Error        | What it's trying to tell you |
| ------------- |:-------------:|
| “No 'Access-Control-Allow-Origin' header is present on the requested resource” | "You are trying to access a server from an address it doesn't know." |
| "HTTP Error 503. The service is unavailable" | (Usually) "Something's going wrong on the server.  Check Terminal or `heroku logs` |
| "$ is not defined" | (Front End) "You didn't include jQuery above this JS file." (Back End) "Don't use jQuery on the back end, there are better tools for that." |
| "Failed to detect set buildpack heroku..." | "We don't know what kind of project (Node? Ruby on Rails?) you're building because we can't find some key files like `package.json`" |
| "Cannot GET /...." (in browser) | "Did you build a route for this?  Did you spell it correctly?" |
| "EADDRINUSE, Address already in use" | "You are already running something on this port" (Usually) "Are you trying to start two web servers on the same port?" |
| "Couldn't connect to server localhost:27017" | "We can't reach Mongo." (Locally) "You didn't start `mongod`" (Heroku) "You didn't set up the Heroku mongo config properly." |
