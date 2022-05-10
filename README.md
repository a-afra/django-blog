<h1 align="center">Django Blog</h1>

<p align="center">
<img src="readme_assets\1.png" alt="HomePage">
</p>


## Description
A blog site with a simple design, built with Django.
I did this project to practice the basics of Django such as:

* Django ORM
* Django migrations
* Django authentication
* Template tags
* And more

This django project has two models including: Account, for user management and Blog, for articles.


## Features
* Register account and Login
<p align="center">
<img src="readme_assets\2.png" alt="signup/login">
</p>

* Create new article
<p align="center">
<img src="readme_assets\3.png" alt="signup/login">
</p>

* View article details
<p align="center">
<img src="readme_assets\4.png" alt="signup/login">
</p>


## Getting started

### Dependencies
First, make sure you have `python3` installed.

Create a virtual environment and activate it:
```bash
python -m venv [directory]
[directory]\Scripts\activate.bat
```
Install dependencies:
```bash
pip install -r requirements.txt
```

### Start the project

Open a terminal at project directory:
```bash
python manage.py runserver
```
The site should be shown up at `http://localhost:8000`
