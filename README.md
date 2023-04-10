# bostonhousepricing

Clone the repository

Create new environment 

```conda create -p boston python==3.9 -y
   conda activate boston/
   pip install -r requirements.txt
   conda install -c anaconda scikit-learn 
```
Kill the PID 
```
lsof -i tcp:5000
kill -9 <PID>
```
All Virtual ENC:
```
conda info --envs

```
Procfile: Commands that needs to be run on Heroku on startup.
Gunicorn is a pure-Python HTTP server for WSGI (Web Server Gateway Interface) applications. It allows you to run any Python application concurrently by running multiple Python processes within a single dyno. It provides a perfect balance of performance, flexibility, and configuration simplicity.

For Dockerfile: COPY takes the content fron (.) working directory to /app folder in the base image working director and then /app becomes that working directory.

DOCKER FILE Parameters from github actions:
HEROKU_EMAIL : Email of github and Heruko
HEROKU_API_KEY : Heroku Account settings > API key
HEROKU_APP_NAME : Heruko APP name