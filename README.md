# URL Shortening Project

## About

Welcome to my URL Shortner Application !
This is a static web-application that compresses large or lengthy urls into short and easy to read links and redirects them to the correct link. This project is made using python programming language and flask web-framework. 

## Installations

- [Python](https://www.python.org/downloads/) v3.8.0 or greater
- [Flask](https://flask.palletsprojects.com/en/2.0.x/installation/#install-flask) (Python Version 3.7 or greater)

## Running on your local machine

1. Download this repository to your local machine. 

```
$ git clone https://github.com/rohangosavi01/url-shortening-project
```

2. Open this folder in your terminal/cmd prompt and run the following code:
```
$ Flask run
```
3. You should see a localhost server running, copy this address into any browser to begin.

## Set-up 

1. The Landing Page consists a form that asks for your long URL. 
2. After you submit the form, website will store this long link in a SQLite3 Database and give you a new short link ready for your use. 
3. Analytics such as date of creation, original and short URL, number of visits can be found under '/stats' page which is encrypted with a username and password.
4. More details can be added as needed with requests made to the SQLite3 Database.
5. Error Handeling ->
   - 404 Page Not Found -> If the user is directed to a page which is not in the server, a 404-Error Page is added to help user navigate back to homepage.

## Descriptions 

- ```__init__.py``` : Program entry point
- ```authentication.py``` : Authenticates the admin username and password for analytics
- ```models.py``` : Adds data to the SQLite3 Database
- ```routes.py and view_ticket.py``` : redirect to correct webpage templates

## Refrences and Learning Outcomes

- Learning Outcomes 
    - Learned more about SQLite3 Database, RDBMS, and Database Models, and how to store data.
    - Learned more about HTML, CSS use with Jinja2 tools to parse variables to display dynammic data. 
    - Learned more about Python Web Application enviornment, HTTP Requests and authentication.

- Python & Flask 
    - https://flask.palletsprojects.com/en/2.0.x/tutorial/index.html
    - https://www.youtube.com/watch?v=Z1RJmh_OqeA&t=1917s

## Photos: 
