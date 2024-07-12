![Prjct Linux](https://github.com/ganeshpandu/images-repo/blob/main/DevOps-Project_Using_Linux.png)

Project: DevOps Automation Pipeline

Tools:

1. AWS EC2
2. Git
3. Jenkins
4. Java
5. Maven
6. Ansible
7. Tomcat
8. SSH
9. GitHub

Project Steps:

1. Launch an AWS EC2 instance with Amazon Linux AMI.
2. Install Git and clone the repository from GitHub.
3. Install Jenkins and configure it to build the project.
4. Install Java and Maven, and set the JAVA_HOME and M2_HOME paths.
5. Create a new Jenkins job to build the project using Maven.
6. Configure the job to deploy the war file to Tomcat using Ansible.
7. Install Ansible on the EC2 instance and configure it to deploy the war file.
8. Create a playbook to deploy the war file to Tomcat.
9. Configure the post-build action in Jenkins to run the Ansible playbook.
10. Test the deployment by accessing the web application URL.

Project Structure:

- GitHub Repository:
    - WebApp (Java project)
    - pom.xml (Maven build file)
- Jenkins Job:
    - Build Project (Maven build)
    - Deploy to Tomcat (Ansible deployment)
- Ansible Playbook:
    - Deploy war file to Tomcat
- EC2 Instance:
    - Tomcat installed and configured
    - Ansible installed and configure
