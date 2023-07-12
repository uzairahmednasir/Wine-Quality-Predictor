1. create folder named `project` and inside that folder create another folder called `Wine-Quality-Predictor` and extract the zip file code into it.
2. navigate into ./project in CLI
3. create a python virtual environment in it using `python -m venv .`
4. activate the virtual environment by running `./Scripts/Activate.ps1` inside projects dir
5. there's a requirement.txt file inside main ./Wine-Quality-Predictor folder copy it back in the ./projects folder
6. then run command `pip install -r requirements.txt` inside that dir, this will install all the necessary libraries that are needed to run this locally
7. when everything is installed go into the project folder inside CLI and then run `python server.py`
8. this will run the flask server and you can go to the given IP address, access the front end input fields and put in the values to test the validity of the project