# LighthouseBNB project
## Project Structure

# Setup related files
docs documentation info
migrations files related to creating the database, and its schema
seeds database fake data used
queries sample database queries

LightBnB_WebApp

public contains all of the HTML, CSS, and client side JavaScript.
index.html is the entry point to the application. It's the only html page because this is a single page application.
javascript contains all of the client side javascript files.
index.js starts up the application by rendering the listings.
network.js manages all ajax requests to the server.

views_manager.js manages which components appear on screen.
components contains all of the individual html components. They are all created using jQuery.

sass contains all of the sass files.
server contains all of the server side and database code.
server.js is the entry point to the application. This connects the routes to the database.
apiRoutes.js and userRoutes.js are responsible for any HTTP requests to /users/something or /api/something.
json is a directory that contains a bunch of dummy data in .json files.

database.js is responsible for all queries to the database.
It doesn't currently connect to any database, all it does is return data from .json files.



