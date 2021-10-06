# ONLINE ASSESSMENT QUIZ

This is an online quiz platform made by Md. Mahtab Noor, Manavi Yadav and Sudhakar Singh Baghel, as the final project of walkover University Program. 

A deployed version can be checked here : 
```https://WalkoverQuiz.mahtab4.repl.co```

# DEMO VIDEO:





https://user-images.githubusercontent.com/88780692/136253097-5d65bb05-bd66-4b20-95d8-0bc86560b3a6.mp4





## We worked for the following specifications:

Assessment shall be MCQ pattern.✔️

There must be a question pool for the assessment.✔️


The questions displayed in the assessment shall be only from that pool.✔️

Number of questions in the pool shall be more than questions displayed.✔️

Set a time limit for the assessment (individual timer for a question/optional).✔️

Question order shall be shuffled for each candidate appearing.✔️

Assessment score shall be generated at the time of submission.✔️

## Admin Panel:

Link of admin Login: We worked for the following specifications:

Assessment shall be MCQ pattern.✔️

There must be a question pool for the assessment.✔️

We have created a pool of 20 - 25 questions in database and randomly selected 10 questions(can be changed by admin) in shuffled order.

The questions displayed in the assessment shall be only from that pool.✔️

Number of questions in the pool shall be more than questions displayed.✔️

Set a time limit for the assessment (individual timer for a question/optional).✔️

Question order shall be shuffled for each candidate appearing.✔️

Assessment score shall be generated at the time of submission.✔️

##Admin Panel:

Link of admin Login: ```https://WalkoverQuiz.mahtab4.repl.co/admin```

admin id: walkover
admin password: 123456


Firstly user have to login to admin panel with  valid email id and password created as superuser


Admin have options to create multiple quizzes.

Admin have options to see scores of all users who attempted the test.

The admin can also add new questions to the question pool using add question option.

The admin can Create test by entering no. of questions which will appear in test and time limit for the test.

Questions will be shuffled for each candidate who take the test.

Admin can also login through test link:
```https://WalkoverQuiz.mahtab4.repl.co/ ```
if they are  superuser, though it does not provide all features of admin, though they can add quizzes, and can see result of all users who submitted their test.

On clicking results of user from dropdown menu , records of all users displayed with details : Name , Score, type of quiz.


## Extra Features:
Simple and easy to use UI.
Login page for storing user's data and validation of the data of users attempting for assessment.
After submission score is displayed with details about each question 
All users' name and score are displayed at the end using database table for storing the data and scores of the user.

## Tech Stack Used:

Frontend -HTML5, CSS3, JavaScript, Ajax and Bootstrap.
Backend - PYTHON DJANGO Framework
Database – SQLITE 

## Deployment:

For Deployment, we have used replit as a platform and uptimerobot to ensure server is running 24/7. 


# CI/CD Setup:

Application is deployed on top of CI/CD pipeline of Replit platform.
Load Balance : Replit automatically manages load balancing.
Availability : For 24/7 availability, we use uptimerobot.



## Project Setup:

## Installations

Make sure to have python version 3 install on your pc or laptop. 
Clone repository 
```https://github.com/MahtabNoor/Quiz_App```
cd Quiz_App

## Installing dependencies

It will install all required dependies in the project.
pip install -r requirements.txt

## Migrations

To run migrations. 
python manage.py makemigrations
python manage.py migrate

## Create superuser

To create super user run. 
python manage.py createsuperuser 
After running this command it will ask for username, password. You can access admin panel from localhost:5000/admin/

## Running locally

To run at localhost. It will run on port 5000 by default.
python manage.py runserver




