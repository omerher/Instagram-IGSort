# Instagram-IGSort

# How to download and run the first time:

1. Clone this repository using "git clone https://github.com/omerher/Instagram-IGSort.git" (If you don't have git installed you can install it from https://git-scm.com/downloads)
2. Create a virtual enviroment (https://uoa-eresearch.github.io/eresearch-cookbook/recipe/2014/11/26/python-virtual-env/ or if you don't want to read that, send the in order: "pip install virtualenv", "virtualenv venv", "venv\Scripts\activate") and install the dependencies with "pip install -r requirements.txt"
3. Run a local redis server by navigating to the "redis" folder and running "redis-server" in the command line. (Keep server running while using the site)
4. Run the flask server (this runs the site) by navigating to the main folder and running "flask run" in the command line. You need to have the virtual enviroment activated. You'll know it's activated if there is a (NAME_OF_VIRTUALENV, if you called the virtual enviroment "venv", that should show) at the start of the line.
5. Go to your browser and enter http://127.0.0.1:5000/.

# How to run after the first time:
1. Navigate to the "Instagram-IGSort" folder.
2. Open a CMD window in the "redis" folder (you can do this by writing "cmd" in the address bar).
3. Write "redis-server" to start the redis server.
4. Open a CMD window in the main folder (you can do this by writing "cmd" in the address bar). Activate the virtual enviroment by writing "NAME_OF_VIRTUALENV\Scripts\activate" where NAME_OF_VIRTUALENV = whatever you called the virtual enviroment (venv if you followed me exactly).
5. Write "flask run".
6. Go to your browser and enter http://127.0.0.1:5000/.

Notes:
- You don't need to have the virtual enviroment activated for running the redis server, but it is required for the flask server.
- The site will only work if both the flask server and redis server are running correctly.
