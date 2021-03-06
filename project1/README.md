# Project 1 - FLASK

## LIVE WEBSITE DEMO

[GoodreadsReviews DEMO](https://goodreadsreview.pythonanywhere.com)

## Requirements

[Project1 requirements - docs.CS50.net](https://docs.cs50.net/web/2018/x/projects/1/project1.html)

## Description of each file

- `application.py` the main app file  
- `import.py` used to import csv data into a configured database  
- `models.py` ORM to setup the database  
- `books.csv` csv data  
- `requirements.txt` dependencies to install

Template descriptions:

- `layout.html` base template with common structure
- `main.html` login/registration/logout page
- `notify.html` after user registration/logout/invalid login credentials
- `members.html` member's area, let users search for a any query
- `search.html` search results page
- `book.html` individual page with book information
- `reviews.html` list all user reviews

### 1. [x] Registration

(At minimum) a username and password.

### 2. [x] Login

Log in using username and password.

### 3. [x] Logout

Logged in users should be able to log out of the site.

### 4. [x] Import

Import books.csv into PostgreSQL database. (SQLite for the live website)

### 5. [x] Search

Once logged in, search for ANY matches on a new page.

### 6. [x] Book Page

Book details and reviews users left on my page.

### 7. [x] Review Submission

One review per user: a rating from 1 to 5 and a review text (optional).

### 8. [x] Goodreads Review Data

Display the average and number of ratings.

### 9. [x] API Access

GET request to your website’s /api/<\isbn> route. Output a json file. Otherwise, a 404 error.
