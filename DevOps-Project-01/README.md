# Deploy your code on a Docker Container using Jenkins on AWS

![AWS](https://imgur.com/Hk28ffE.png)

**In this blog, we are going to deploy a Java Web app on a Docker Container built on an EC2 Instance through the use of Jenkins.**

### Agenda

* Setup Jenkins
* Setup & Configure Maven and Git
* Integrating GitHub and Maven with Jenkins
* Setup Docker Host
* Integrate Docker with Jenkins
* Automate the Build and Deploy process using Jenkins
* Test the deployment

### Prerequisites

* AWS Account
* Git/ Github Account with the Source Code
* A local machine with CLI Access
* Familiarity with Docker and Git

Step 1: Set up Jenkins on an EC2 instance

- Create a new EC2 instance on AWS
- Install Jenkins on the instance using the official Jenkins image
- Configure Jenkins to run on port 8080
- Set up the Jenkins user and password

Step 2: Integrate GitHub with Jenkins     

- Create a new GitHub repository for your project
- Install the GitHub plugin in Jenkins
- Configure the GitHub plugin to connect to your repository
- Set up a webhook to trigger Jenkins builds on push events

Step 3: Integrate Maven with Jenkins

- Install Maven on the EC2 instance
- Configure Maven to work with Jenkins
- Set up a Maven project in Jenkins
- Configure the Maven project to build your Java web app

Step 4: Set up a Docker host on an EC2 instance

- Create a new EC2 instance on AWS
- Install Docker on the instance
- Configure Docker to run on the instance

Step 5: Integrate Docker with Jenkins

- Install the Docker plugin in Jenkins
- Configure the Docker plugin to connect to your Docker host
- Set up a Docker container to run your Java web app

Step 6: Create a Jenkins job to build and copy artifacts to the Docker host

- Create a new Jenkins job
- Configure the job to build your Maven project
- Configure the job to copy the artifacts to the Docker host
- Set up a post-build action to deploy the artifacts to the Docker container

Step 7: Update the Dockerfile to copy artifacts and launch a new container

- Update the Dockerfile to copy the artifacts from the Jenkins job
- Configure the Dockerfile to launch a new container with the copied artifacts

Step 8: Automate the build and deployment process using Jenkins

- Configure the Jenkins job to run automatically on push events
- Set up a pipeline in Jenkins to automate the build and deployment process
- Configure the pipeline to run the Jenkins job and deploy the artifacts to the Docker container
