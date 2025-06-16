WELCOME TO THE DOCKER PROJECT 1 

Project Title: "A basic Flask web app containerized with Docker"

1. Project Overview:
You will learn how to containerize a basic web application using docker.
How to build and run the docker images.
Running a web app in a containerize environment 

2. Technologies Used:
Python 3.9
Flask
Docker
Docker CLI
Linux Distro

3. Instructions to perform this Project 
The first step is to create a basic web server using Flask you can copy and paste it from my repository as I have provided 
The second step is to create a requirement file already provided in my repository.
The third step is to write the Docker file.
Now build the image use this command (docker build -t flask-app . )
After building the image now run the container in which map the container with the port so it can be access from the web use this command (docker run -p 8080:80 flask-app)
Now try to access the app from web type in browser (localhost:8080)

4.Troubleshooting Steps:
If you face any issue in creating the image from your docker file review the docker file carefully.
Some time also the flask app that we have created in first step the mistake can also be in that file
If you run your container and it give you an error that say port is already in use than use this command instead (docker run -p 8081:80 flask-app)

Learning Outcomes:
