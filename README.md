## Demo Project - Complete CI/CD Pipeline with EKS and AWS ECR

### Topics of the Demo Project
Complete CI/CD Pipeline with EKS and AWS ECR

### Technologies Used
- Kubernetes
- Jenkins
- AWS EKS
- AWS ECR
- Java
- Maven
- Linux
- Docker
- Git

### Project Description
- Create a private AWS ECR Docker repository
- Create credentials for the ECR repository in Jenkins
- Create a Secret for AWS ECR
- Adjust Jenkinsfile to build and push Docker Image to AWS ECR
- So the complete CI/CD project we build has the following configuration:
  - a. CI step: Increment version
  - b. CI step: Build artifact for Java Maven application
  - c. CI step: Build and push Docker image to AWS ECR
  - d. CD step: Deploy new application version to EKS cluster
  - e. CD step: Commit the version update

