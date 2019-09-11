# project1
CS50 Project 1: Book Search
## Web Programming with Python and JavaScript
### https://courses.edx.org/courses/course-v1:HarvardX+CS50W+Web/course/

## Use the app on Heroku

## Usage

# A website where folks can search for a book and find the book info
# together with user average rating.  Then they can also leave a comment at that

* Create an account
* Search books by name, author or ISBN
* Get info about a book and submit your own comment/review!

# Clone repo
$ git clone https://github.com/marcorichetta/cs50-project1.git

$ cd cs50-project1

# Install all dependencies
$ pip install -r requirements.txt

# ENV Variables
1.)  First from the command line set the environment variables by typing
$ export FLASK_APP = application.py # flask run
$ export DATABASE_URL = Heroku Postgres DB URI
$ export GOODREADS_KEY = Goodreads API Key. # More info: https://www.goodreads.com/api

2.)  The script import.py to load in the csv file is with the csv file
  being imported in the books db.

3.)  Ok lots of files to describe
  application.py has all of the program logic, routes, queries. 
  html files:  
    a.)  layout.html gives an overall layout to the site, great so I only need
    b.)  index.html is the main login page
    c.)  results.html show the results after looking up a book in the database
    d.)  book.html shows the book page for a given ISBN
    e.)  login.html is the destination the route login sends you upon loggging in or registering
    
