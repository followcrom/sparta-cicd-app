# Sparta CI/CD App

![alt text](imgs/cicd-pipeline3.jpg)

## What is CI/CD?

CI/CD stands for Continuous Integration/Continuous Deployment. It is a set of practices and tools that enable developers to frequently merge code changes into a shared repository, and then deploy the changes to production after automated testing and verification.

## When to use CI/CD?

CI/CD should be used when you want to automate the process of integrating code changes into a shared repository and deploying the changes to production. This can help you to catch bugs early, reduce the risk of deployment failures, and increase the speed of development.

## How to use CI/CD?

To use CI/CD, you need to set up a CI/CD pipeline that automates the process of integrating code changes into a shared repository and deploying the changes to production. This typically involves setting up a version control system, a build server, and a deployment server, and configuring them to work together.

## Why use CI/CD?

CI/CD can help you to catch bugs early, reduce the risk of deployment failures, and increase the speed of development. By automating the process of integrating code changes into a shared repository and deploying the changes to production, you can ensure that your code is always in a deployable state and that you can quickly and easily deploy new features and fixes to production.

## Where to use CI/CD?

CI/CD can be used in any software development project where you want to automate the process of integrating code changes into a shared repository and deploying the changes to production. This includes web applications, mobile applications, and desktop applications.

![alt text](imgs/cicd-pipeline.jpg)

## How to Use Jenkins

1. Install Jenkins on your server (optional)
2. Set up a Jenkins job. From the Jenkins dashboard, click on "New Item" to create a new job.
3. Configure the job to build your project
4. To run the job, click on "Build Now" from the job page.
5. From build history, you can see the status of the build and view the console output.

![alt text](imgs/cicd-pipeline2.jpg)

## Add SSH Key to Jenkins

1. Generate an SSH key pair.
2. Add the public key to your Git repository
3. Add the private key to Jenkins
4. Configure your Jenkins job to use the SSH key


# How to open VS Code from the terminal

`code .`

If you're not in the directory of your project, replace . with the path to your project directory.

Launching VS Code from an environment where your SSH agent is running ensures that all child processes, including Git operations initiated from the Source Control panel, inherit the SSH authentication context, thus avoiding permission issues with remote repositories over SSH.

## SDLC


cd app

npm install

npm test