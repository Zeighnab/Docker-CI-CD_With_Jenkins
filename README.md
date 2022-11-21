# Docker CI In Jenkins

This project demonstrate continous integration using jenkins, and also building and archiving image using docker.

## Tools:
1. Git
2. Jenkins
3. Sonarqube
4. Docker
5. Amazon ECR (Elastic Container Registry)
6. Amazon ECS (Elastic Container Service)

## Steps:

* Install docker engine in Jenkins
  * Add jenkins user to docker group & reboot
* Install AWS cli
* Create IAM User
* Create ECR repo
* Plugins
  * Ecr, docker pipeline, aws sdk for credentials
* Store aws credentials in jenkins
* Run the pipeline

