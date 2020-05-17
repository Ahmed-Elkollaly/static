## Project Overview

Simple CI/CD pipeline to upload file to AWS S3 to act as static website 

### Project Features
* CI/CD Pipeline in Jenkins
* Upload files to AWS

## Pipeline
* Lint : Lintting html file
* Upload : Upload file to AWS S3

![Images show Jenkins pipeline](https://user-images.githubusercontent.com/25865668/82160248-421d0000-9894-11ea-889c-0a90beb8ae7a.png)

Note: `Jenkinsfile` contains more information about the pipeline

---

## Setup the Environment
* Create AWS S3 bucket and make it public
* Setup AWS S3 bucket to act as static hosting
* Install Jenkins on your server or locally 
* Change S3 bucket name in `Jenkinsfile` 
* Link Jenkins with Github
* Run the pipeline
