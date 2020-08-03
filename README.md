# DevOps_Microservices
Cloud DevOps Engineer Nanodegree - Operationalize a Machine Learning Microservice API
Project Overview
In this project we had to operationalize a Machine Learning Microservice API which uses a pre-trained, sklearn model that has been trained to predict housing prices in Boston according to several features, such as average rooms in a home and data about highway access, teacher-to-pupil ratios, and so on. You can read more about the data, which was initially taken from Kaggle, on the data source site. This project tests your ability to operationalize a Python flask app—in a provided file, app.py—that serves out predictions (inference) about housing prices through API calls. This project could be extended to any pre-trained machine learning model, such as those for image recognition and data labeling.

Setup the Environment
Run git clone https://github.com/rohan2907/DevOps_Microservices.git
Run cd project-ml-microservice-kubernetes
Run python3 -m venv ~/.devops
Run source ~/.devops/bin/activate
Run make install to install the necessary dependencies
Installing Docker
Create docker account
Install the lastest stable release
Run docker --version
Installing Kubernetes
Mac
Run brew cask install virtualbox to install VirtualBox
Run brew cask install minikube to install minikube
Windows
Install VirtualBox
Install minikube
Configure Kubernetes to Run Locally
run minikube start
Running app.py
Standalone: python app.py
Run in Docker: ./run_docker.sh
Run in Kubernetes: ./run_kubernetes.sh
Kubernetes Steps
Setup and Configure Docker locally
Setup and Configure Kubernetes locally
Create Flask app in Container
Run via kubectl
