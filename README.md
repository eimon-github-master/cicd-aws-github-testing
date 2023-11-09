# cicd-aws-github-testing

Exciting Update: Just completed a mini project on GitHub Workflow-EKS-CICD! 
In this hands-on project, we started by manually creating an AWS EKS cluster, and later, we'll test it with CI/CD.
We recently had the opportunity to dive into the world of #DevOps and #Kubernetes by working on a mini project that 
involved setting up a continuous integration and continuous deployment (CI/CD) pipeline using AWS EKS, GitHub, and Docker Hub. 

Here are the steps I followed:
Install eksctl: Download and install eksctl to manage Amazon EKS clusters.
Install kubectl: Downlaod and Install the Kubernetes command-line tool kubectl to interact with the Kubernetes cluster.
Create EKS Cluster: Create an EKS cluster with a single node on AWS using eksctl.
Set Up Repositories: Created repositories on Docker Hub and GitHub for the project.
Configure Secrets: Set up sensitive information (Docker Hub credentials, AWS access keys) securely in GitHub Actions secrets.
Push to GitHub: Pushed necessary files (.github/workflows/main.yml, Dockerfile, app.py, k8/deployment.yaml) to the GitHub repository.
Automated CI/CD: Set up a GitHub Action workflow to automatically build and test the application.

View Results: The GitHub Action automatically built and tested the application, which can be accessed at: http://18.143.161.231:31010
Success!: The project passed the tests, and the result is "Welcome HelloCloud!" 

Important Note: Don't forget to configure your security group in the EC2 instance to allow traffic on port 31010.
This project was a fantastic learning experience, and I'm thrilled to have successfully set up a CI/CD pipeline on AWS EKS using GitHub Actions. 
The power of automation in software development is truly remarkable! 


![GithubWorkFlow-EKS-CICD](https://github.com/eimon-github-testing/cicd-aws-github-testing/assets/142704627/7dae6bba-b7e9-4512-93f7-fae2b705166e)
