# Flask

This repository contains file used to develop a basic Flask application.

Pre-requisite knowledge:
-Python
-Basic HTML

Library need:
- flask
- Flask, render_template, request, redirect, url_for, jsonify (All in flask)

Steps Followed:
- Check whether conda is added to the path, if not add that by going to the environment variables
- Create a folder on the desired location and open that in VS code
- Created an conda environment using command "conda create -p venv python==3.11 -y"
- Activate the environment with command conda activate "C:\Users\<user-name>\Flask Practice\venv"
- install flask library to the environment
- name the flask as app
- set 'debug=True' in app.run to automatically update the page everytime
- Create different function using @app.route
- Link function with HTML page using render_template and url_for library

Thing Learned:
- Creating an envirnoment
- usage of flask library
- @app.routs("/") means the root page that is laoded at first
- Use 'jinja' feature in flask to access varibles or any type of data in html page using double curly brackets({{}})
- Two type of methods that are "GET" and "POST", GET used in simple scenario where only URL is enough to access the webpage but POST used when we have to pass some data along URL
- @app.route should have a function just below it, telling what that page meant to do
- "Variable rule" can be used with URL when specifing the type of the variable like "@app.route('success/int:score)", check that URL variable name should matchs the one used in the function
- Both GET and POST methods can be passed through URL using if else condition and we can redirect one webpage to different ones based on the condtion and redirect and url_for methods
- Json file can also be accessed using get_json method of the flask</br></br></br>

Reference: Complete Python Flask Tutorial For Data Science Projects In Hindi, Krish Naik Hindi, https://www.youtube.com/watch?v=KF-rDqQfqz0
