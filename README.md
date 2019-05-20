# ML-React-App
It's a template on which we can build a React app and call endpoints to make predictions.

Starting the template
Clone the repo to your computer and go inside it and open two terminals here.

Preparing the UI
In the first terminal, go inside the ui folder using cd ui. Make sure you are using the node version 10.4.1. Once inside the folder, run the command yarn install to install all dependencies.

To run the UI on server, we will use serve. We will begin by installing the serve globally, post which, we’ll build our application and then finally run the UI using serve on port 3000.



npm install -g serve


npm run build


serve -s build -l 3000


You can now go to localhost:3000 to see that the UI is up and running. But it won’t interact with the Flask service which is still not up




install virtual environment on Ubuntu : https://gist.github.com/Geoyi/d9fab4f609e9f75941946be45000632b


-on Ubuntu 
Install pip first
sudo apt-get install python3-pip


-Now create a virtual environment
virtualenv venv 


-Active your virtual environment:
source venv/bin/activate

-finally run the Flask service so it can interact with UI
FLASK_APP=app.py flask run

 * Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)

   