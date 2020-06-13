# Instagram-IGSort

How to run:

1. Create a virtual enviroment and install the dependencies with "pip install -r requirements.txt"
2. Run a local redis server by navigating to the "redis" folder and running "redis-server" in the command line. (Keep server running while using the site)
3. Run the flask server (this runs the site) by navigating to the main folder and running "flask run" in the command line. You need to have the virtual enviroment activated. You'll know it's activated if there is a (NAME_OF_VIRTUALENV) at the start of the line.
4. Go to your browser and enter http://127.0.0.1:5000/.

Notes:
- You don't need to have the virtual enviroment activated for running the redis server, but it is required for the flask server.
- The site will only work if both the flask server and redis server are running correctly.
