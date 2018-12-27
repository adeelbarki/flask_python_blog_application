# Blog Application in Flask PYTHON (Version 1.0.1)

## Description

This project is developed in flask and python. It is a blog application created for software blogs from different authors. 

This application is designed for the learning process of Flask Python project.
It is currently in testing phase and running in deployment mode. 

Visit live application at http://adeelbarki.com

## Features

This demo website is actually a real blog website that has certain features:

* App is build in flask and database used is sqlite. 
* Registration and Login Forms
* Forgot Password with email verification(_Read below Email Verification_)
* Posting, updating & deleting a blog
* Order blogs using priority and pagination
* Blogs filter by author

## Email Verification

In case, if this repo is cloned. Email verification will not work unless a sender email is provided. After cloning this project, follow these instructions to run the application perfectly.

* Turn on `Less secure app access` in your Gmail Account Security.
* `$ cd blog/users` into the directory and open `utils.py`. In line 28, 
`sender='youremail@gmail.com` change youremail to your own gmail account. Email smtp protocol settings can be found in `blog/config.py`.
* Enviorment Variable must be set for secret key, email and password in order to run _forgot your password_ on this application. For more info, kindly email at adeelbarki@gmail.com or see how to set environment variable on desired operation systems


## Upcoming Features

_More features will be included in next version of app._
_Next Upgrade includes Like button and comment on specific post._


## Source Code

For source code visit my [github repo](https://github.com/adeelbarki/flask_python_blog_application)

In order to run it locally, clone the github repo in your local machine.

`$ git clone https://github.com/adeelbarki/flask_python_blog_application.git`

To run this application, simply run this command in flask_python_blog_application folder.

`$ python run.py`

Python version 3.6 must be installed for better performance.

## Course

This is a sample project designed during Udacity NanoDegree Full Stack Web Development Course. 

## Credits

Special thanks to [Core Schafer](https://www.youtube.com/user/schafer5/about) for excellent lectures and teaching Python & other programming languages. 

## Author

Adeel Barki
_Full Stack Engineer / Electronics Engineer_
* Email(Contact): _adeelbarki@gmail.com_
* LinkedIn: _https://www.linkedin.com/in/adeelbarki/_
* twitter: _https://twitter.com/adeelbarki_
* Facebook: _https://www.facebook.com/adeelbarki_






