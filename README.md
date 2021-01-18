# Bank-Note-Authentication-End-to-End-with-Docker
End to end deployment of Machine Learning Project using Docker Desktop 

# Docker

## Why Docker

1. Enviroment Standardization - It standardizes the environment.
2. Build once deploy it anywhere.
3. Docker enables more efficient use of system resources.
4. Docker enables faster software delivery cycles. 
5. Docker enables application portability. 
6. Isolation - Advantageous over Virtual Machine. 

Created over OS. Each has its own process id, network configuration (port no.), user route folder.

## What is Docker

A container is a standard unit of software that packages up code and all its dependencies so the application runs quickly and reliably from one computing environment to another. A Docker container image is a lightweight, standalone, executable package of software that includes everything needed to run an application: code, runtime, system tools, system libraries and settings.

Container images become containers at runtime and in the case of Docker containers - images become containers when they run on Docker Engine. Available for both Linux and Windows-based applications, containerized software will always run the same, regardless of the infrastructure. Containers isolate software from its environment and ensure that it works uniformly despite differences for instance between development and staging.

Docker containers that run on Docker Engine:

* Standard: Docker created the industry standard for containers, so they could be portable anywhere
* Lightweight: Containers share the machine’s OS system kernel and therefore do not require an OS per application, driving higher server efficiencies and reducing server and licensing costs
* Secure: Applications are safer in containers and Docker provides the strongest default isolation capabilities in the industry

WSGI - Web Server Gateway Interface
Web Server communicate with Flask Web App using WSGI. 


## How to start with Docker

To start with Docker one need to create a base image that will be downloaded from docker hub.

Base Image is an image of required basic OS e.g. Linux Ubuntu. A docker image starts with a base image. On top of a base image various components can be added e.g. Anaconda Python 3.6. On top of that flask and flasgger. Encapsulation of all this will be the docker image. Once the docker image is created it is then dockerized. After dockerizing one can easily take this to any other similar base image environment, and install the web app.

## Some basic Docker Commands
1. FROM 
2. COPY
3. EXPOSE
4. WORKDIR
5. RUN
6. CMD

The BankNote_Authentication.csv contains the data. Problem Statement and Model file contains the problem statement and trained model. The model is then stored in classfier.pkl file. Flask_api contains Flask api and Streamlit_api contains Streamlit api code. Dockerfile contains command regarding the docker implementations of the project.
