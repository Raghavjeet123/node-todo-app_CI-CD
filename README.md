# node-app_CI-CD
Creating the nodejs app and Create CI/CD pipeline 


Here is the simplified version of your entire documentation:

CI/CD Pipeline for Node.js Application Using Jenkins and Docker
This guide will show you how to set up Continuous Integration and Continuous Deployment (CI/CD) for a Node.js app using Jenkins and Docker on an AWS EC2 server.

Table of Contents:
Prerequisites for Setting Up the CI/CD Pipeline -
Step 1: Fork or Create a Node.js Application
Step 2: Push the Application to GitHub
Step 3: Clone the Repository on EC2 Instance
Step 4: Create a Dockerfile for the Node.js Application
Step 5: Install Jenkins on EC2
Step 6: Configure Jenkins for CI/CD
Step 7: Run the Build and Deployment


Prerequisites 
Before you start the whole process, make sure you have the following:

- An AWS EC2 server:                                 This is where your application will be hosted. You need to create an EC2 instance (a virtual server) on AWS that you can access via SSH.
- Docker and Git installed on the EC2 server:        Docker is needed to containerize your application, and Git is used to clone your code from GitHub. Install Docker and Git on the EC2 instance.
- Jenkins installed and running on the EC2 server:   Jenkins is a tool that automates the CI/CD process. You need to download and set up Jenkins on your EC2 instance.
- A GitHub account:                                  You will use GitHub to store your application's source code. Make sure you have a GitHub account where you can push your Node.js application.


 -> A GitHub account.
Step 1: Fork or Create a Node.js Application
Fork an existing repository or create a new Node.js app:

To fork, click the "Fork" button on the chosen GitHub repo.
To create a new app, run: 
->                          mkdir my-nodejs-app
->                          cd my-nodejs-app
->                          npm init -y
