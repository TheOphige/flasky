#Mention the base image 
FROM python:3.9.18-slim-bullseye

#Copy the current folder structure and content to docker folder
COPY . /usr/ML/app

#Expose the port within docker 
EXPOSE 5000

#Set current working directory
WORKDIR /usr/ML/app

#Install the required libraries
RUN pip install -r requirements.txt

#container start up command
CMD python flask_api.py
