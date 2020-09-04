# Azure CI/CD Pipelines 

### Overview

Built a Continuous Delivery pipeline that deploys a Flask machine learning app using Azure Pipelines to Azure App
Services. Used Github Actions and application code to perform the initial lint, test and install cycle on my app 
running Flask in Azure App Services.

Integrated Continuous Delivery using Azure Pipelines to deploy my tested app changes automatically to production 
wrapping everything up with final testing of the prediction capability of my app deployed into production 

### Technologies
Azure Pipelines, Azure App Services, Continuous Integration and Continuous Delivery (CI/CD), Docker, Github Actions, 
Flask, Kubernetes, Machine Learning, MS Azure, Pandas, Pylint, Pytest, Python, Scikit-Learn.

### Running the App Locally with Docker
To run the app locally you need to be running Docker. Go to the flask-sklearn directory and execute 
the script to start a container running the app:

>$ cd flask-sklearn
>$ ./run_docker.sh

Open a new terminal, go to the same directory and execute the client call:

>$ cd flask-sklearn
>$ ./make_prediction.sh

You can adjust the prediction by editing the CURL call in that script.