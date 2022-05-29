# Facial Recognition Attendance Project Engage 2022

## Quick demo
![](demo.gif)

### Presenation Demo link :
Link: [Video Link]()

## Project presenation Slides & Screenshots :
Link: [PPT Link](https://drive.google.com/drive/folders/1Wrg9rHVB-DrY8zVcemzc752D4vVuEZ3n?usp=sharing)

## Run-through                   
* A simple facial recognition project that detects a student's face and records his or her attendance in a database and an excel file.
* It can also generate an attendance report and send or save it as a pdf file with a subject and title.
* It can also be used as a student management portal, displaying all students' information and attendance on a dashboard ,having a chat-bot to answer all queries. 

## Basic Functionality
This project is divided into multiple parts:-
1. Images are captured, a model is trained, and a face is detected.
2. Dashboard This displays all students who are present as well as those who are absent, and a user can access the dashboard to view, update, and  delete students .It also has a chat-bot for queries and the alert message after the attendance is recorded.
3. It creates a excel sheets one for current attendance and another which adds the unique students.
4. A section where we can select the files and send it via mail with subject and title

## Technologies Used
### Frontend
* HTML 
* CSS 
* BOOTSTRAP
### Backend
* Python ( backend programming language )
* Django (web development framework)
* OpenCV ( Computer Vision Library )

## Installation
The Code is written in Python 3.8 which can be  installed from [here](https://www.python.org/downloads/). If you are using a lower version of Python you can run this or upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:-
```bash
pip install -r requirements.txt
```
##
After cloning check that all the libraries are installed or use the .idea environment given in the repo.
For running the same project go to the project folder where the **manage.py** file is located and run the following command into the command prompt:-
```bash
python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```
## Other installation info :
1.In the admin file create a new admin with the command : python manage.py createsuperuser 

## Credentials:
1. The login credential used my me :
    usename:rider
    password:123

## Directory Tree 
```
├── face_recognition_system (application folder)
│   ├── face_rec
|       ├── migrations
|       ├── templates (html files are stored here)
|       ├── admin.py (admin related data is stored here)
|       ├── apps.py (information related to this application is stored here)
|       ├── info (Document containing the Screenshots of the website pages)
|       ├── models.py (database information is stored here)
|       ├── tests.py 
|       ├── urls.py (urls related to this project are stored here)
|       └── views.py (the working of each url is stored in a view)
│   ├── face_recognition_system (project folder)
│       ├── asgi.py
|       ├── settings.py (main file where all the information is stored)
|       ├── urls.py (urls are redirected to urls file of application)
|       └── wsgi.py (this file is used to run the project when deploying,I tried on Heroku)
|   ├── requirements.txt
|   ├── Procfile (it contains info on how to run the application when deployed)
|   ├── README.md (markdown file or documentation of this project)
|   └── manage.py (this file is used to run the project on client side)
```
