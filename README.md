# GWA - Gym Web App

![Alt text](./src/main/webapp/images/GWA_logo.svg?raw=true)

## Group members
| Surname      | Name          |
| ------------ | ------------- |
| Alessio      | Marco         |
| Caldivezzi   | Francesco     |
| Campeol      | Alberto       |
| D'Antimo     | Simone        |
| Forzan       | Riccardo      |
| Freskina     | Fatjon        |
| Pasin        | Andrea        |
| Singh        | Harjot        |
| Tumiati      | Riccardo      |


## Overview
* [General description of the web-app](#general-description-of-the-web-app)
* [Users of the web app](#users-of-the-web-app)
* [Necessary steps before usage](#necessary-steps-before-usage)

## <a name="general-description-of-the-web-app"></a> General description of the web app 
This web application is designed to be used for the management of a gym. It can be used by both the users attending the various courses offered by the gym and by the trainers/secretaries.<br />
The aim of this web application is to simplify the users' tasks, allowing to manage courses, attendances and subscriptions with only a few clicks.

## <a name="users-of-the-web-app"></a> Users of the web app
This web application has been implemented for different users, each one of them having different functionalities available.
### Guest
The Guest represents a user who accesses the web application without logging in. He will be able to have a general insight of the gym.
### Trainee
The Trainee represents a logged-in user that attends courses in the gym. Each Trainee can manage his/her personal information and books lectures for the courses he is subscribed to.
### Trainer
The Trainer represents a logged-in user who teaches one or more courses. Each Trainer can manage his/her personal information and manage the attendances for the courses he/she teaches.
### Secretary
The Secretary represents a logged-in user who takes care of the correct and timely management of secretarial activities regarding the gym.

## <a name="necessary-steps-before-usage"></a>Necessary steps before usage
To make this webapp working correctly you need to :
- create a folder inside the tomcat web server installation folder called `gwa`
- then go inside gwa and create two other subdirectories called : `avatars` and `medical_certificates`

To make the email system working correctly you also need to put the image
located at `src/main/webapp/images/logo.jpg` in the `gwa` folder located inside your tomcat web server installation folder

Before using this webapp you have to create and eventually populate the database.<br />
You can follow the instructions in `src/main/java/database/README.md`.<br />
We have also created a Java class with path `src/main/java/database/DataBaseUtils.java` which allows you to create and populate your local database easily.
 
