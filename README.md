## Project Overview

Simple CI/CD pipeline to upload file to AWS S3 to act as static website 

### Project Features
* CI/CD Pipeline in Jenkins
* Upload files to AWS

## Pipeline
* Lint : Lintting html file
* Upload : Upload file to AWS S3

![Images show Jenkins pipeline](screenshot-08.png)

Note: `Jenkinsfile` contains more information about the pipeline

---

## Setup the Environment
* Create AWS S3 bucket and make it public
* Setup AWS S3 bucket to act as static hosting
* Install Jenkins on your server or locally 
* Change S3 bucket name in `Jenkinsfile` 
* Link Jenkins with Github
* Run the pipeline
