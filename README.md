# Micro_service_project
status badge:
[![CircleCI](https://circleci.com/gh/MaiRabie/Micro_service_project/tree/main.svg?style=svg)](https://circleci.com/gh/MaiRabie/Micro_service_project/tree/main)
***********************************************************
All the info is described in the pdf with a screen shoots for each task please check it 

Summary of the project:
This project helps me to apply the skills I have acquired in this course to operationalize a Machine Learning Microservice API.
Applying Docker and Kubernetes concepts to predict housing prices in Boston.
The Docker technology uses the Linux kernel and features of the kernel, to segregate processes so they can run independently.
Kubernetes is a portable, extensible, open-source platform for managing containerized workloads and services, that facilitates both declarative configuration and automation.


Files in the Repository:
1- .circleci/config.yml : Defines an automated testing environment; CircleCI uses a YAML file to identify how you want your testing environment set up and what tests you want to run.
2- output_txt_files : The requirements results are copied here.
3- app.py : file contained the pre-trained model prediction. 
4- Dockerfile : The Dockerfile contains all the commands a user could call on the command line to assemble an image.
5- make_prediction.sh : This script is responsible for sending some input data to your containerized application via the appropriate port. Each numerical value in here represents some feature that is important for determining the price of a house in Boston.
6- Makefile : this is includes instructions on environment setup and lint tests.
7- requirements.txt : contain all the dependencies that need to be installed.
8- run_docker.sh : You can find a list of all the docker commands to build and run the docker image that is defined in the Dockerfile.
9- run_kubernetes.sh : This is used to deploy your application on the Kubernetes cluster, This assumes you have a local cluster configured and running. This script should create a pod with a name specified.
10- upload_docker.sh : This script upload the built image to docker. This will make it accessible to a Kubernets cluster.
