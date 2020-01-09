### Instagram

## Author
 Samuel Odhiambo A.

## Description
 Creating a clone of the website for the popular photo app Instagram

## Setup Instructions:
## Requirements
1. Clone the repository
 Clone the the repository by running

 https://github.com/s-odhiambo/Instagram.git
 or download a zip file of the project from github

 Navigate to the project directory

 cd instaKlone
2. Create a virtual environment
 Install Virtualenv

 pip install virtualenv
 To create a virtual environment named virtual, run

 virtualenv virtual
 To activate the virtual environment we just created, run

 source virtual/bin/activate
3. Create a database
 You'll need to create a new postgress database, Type the following command to access postgress

 $ psql
 Then run the following query to create a new database named instaklone

# create database Instagram
4.Install dependencies
 To install the requirements from requirements.txt file,

 ## pip install -r requirements.txt
5.Create Database migrations
 Making migrations on postgres using django

## python3 manage.py makemigrations insta
 then run the command below;

 ## python3 manage.py migrate
6.Run the app
 To run the application on your development machine,

## python3 manage.py runserver
 Running Tests
 To run tests;

## python3 manage.py test
 Technologies Used
 Django
 Python
 Html
 Css
 Javascript
 Bootstrap
## User stories
 As a user of the application I should be able to:
 
 Sign in to the application to start using.
 Upload my pictures to the application.
 See my profile with all my pictures.
 Follow other users and see their pictures on my timeline.
 Like a picture and leave a comment on it.
## Bugs
 There are no know bugs at the moment

## License
 License

 MIT license © 2019 Samuel Odhiambo

## Collaboration Information
 Clone the repository
 Make changes and write tests
 Push changes to github
 Create a pull request
 Contacts
 Reach me on:

 Email: samuelangienda1998@gmail.com

