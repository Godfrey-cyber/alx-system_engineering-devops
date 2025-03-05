# 0x1A. Application server
## Set up development with Python
	- Let’s serve what you built for AirBnB clone v2 - Web framework on web-01. This task is an exercise in setting up your development environment, which is used for testing and debugging your code before deploying it to production.
##  Set up production with Gunicorn
	- Install Gunicorn and any other libraries required by your application.
The Flask application object should be called app. (This will allow us to run and check your code)
## Serve a page with Nginx
	- Building on your work in the previous tasks, configure Nginx to serve your page from the route /airbnb-onepage/
## Add a route with query parameters
	- Building on what you did in the previous tasks, let’s expand our web application by adding another service for Gunicorn to handle. In AirBnB_clone_v2/web_flask/6-number_odd_or_even, the route /number_odd_or_even/<int:n> should already be defined to render a page telling you whether an integer is odd or even. You’ll need to configure Nginx to proxy HTTP requests to the route /airbnb-dynamic/number_odd_or_even/(any integer) to a Gunicorn instance listening on port 5001. The key to this exercise is getting Nginx configured to proxy requests to processes listening on two different ports. You are not expected to keep your application server processes running. If you want to know how to run multiple instances of Gunicorn without having multiple terminals open, see tips below.
## Let's do this for your API
	- Let’s serve what you built for AirBnB clone v3 - RESTful API on web-01
## Serve your AirBnB clone
	- Let’s serve what you built for AirBnB clone - Web dynamic on web-01.

## Deploy it!
	-Write a systemd script which starts a Gunicorn process to serve the same content as the previous task (web_dynamic/2-hbnb.py)
## No service interruption
	-
