# Overview

This is my first attempt at creating a web app with a framework. This is my first time using Django. I just wanted to learn the basic framework of how this web app works and figure out the basic functionality of it. Im already familiar with python and web front end technologies but combining them was a challenge. The purpose of this web app was to be able to create a website where users could come in and vote on questions. With the Django Admin you can create additional questions, view the amount of votes and edit question and answers. 

I ran the server that comes with the functionality that you can turn on from the command line.
Once starting the server up, navigate to /polls/.
Its hosts the main functionlity of the page.
[Software Demo Video](https://youtu.be/_D5FhQKug_A)

# Web Pages

There there are 4 main pages:
The admin page(not really a page) - Allows admin to add and remove question and answers
Polls page - Delivered by the index page. Questions pully from sqlite db
Voting page - Delivered by the detail page, basic radio form, pulls from db
Results page - Delivered by results page, pull from db

# Development Environment

Django 3.1.7
Python 3.9.0
VS Code
# Useful Websites

{Make a list of websites that you found helpful in this project}
* [Django Documentationi](https://www.djangoproject.com/)
* [Stack Overflow](https://stackoverflow.com/)

# Future Work
* Finish CSS/ frontend and layout
* Allow for multiple polls on a single page
* Add login functionality and accounts