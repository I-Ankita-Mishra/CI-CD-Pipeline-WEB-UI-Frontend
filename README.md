# Kaiburr Task 5: CI-CD Pipeline for React Application

This repository demonstrates the setup and configuration of a Continuous Integration and Continuous Deployment (CICD) pipeline for a React application deployed to an AWS S3 bucket.

## Table of Contents

- [Project Structure](#project-structure)
- [Key Features](#key-features)
- [Technologies Used](#technologies-used)
- [Requirements](#requirements)
- [How the Task Is Made](#how-the-task-is-made)
- [Screenshots](#screenshots)

## Project Structure
The project is structured as follows:

- `build/`: The output folder containing the React application files.
- `codebuild/`: AWS CodeBuild configuration file.
  - `.codebuild.yaml`
- `README.md`: This README file.
   
## Key Features
- Automates the build and deployment of an React application to an S3 bucket.
- Uses AWS CodePipeline for setting up a CICD pipeline.
- Demonstrates integration with AWS CodeBuild for building the React app.
- Enables a static website hosted on an S3 bucket.

## Technologies Used
- React: Frontend framework
- AWS S3: Object storage service for hosting the website
- AWS CodePipeline: CICD service for automating the deployment process
- AWS CodeBuild: Service for building the React application
- Git: Version control system
- Node.js: JavaScript runtime for React development


## Requirements

Before setting up the CICD pipeline, ensure you have the following:

- An AWS account with appropriate permissions.
- The React application codebase.
- AWS CLI configured with the necessary credentials.
- Git installed on your local machine.


## How the Task Is Made

Follow the AWS documentation and the screenshots provided in the "Screenshots" section to set up the CICD pipeline.
The CICD pipeline automates the following steps:
- Creates an S3 bucket to host the React application.
- Builds the React application using npm run build.
- Uploads the application files to the S3 bucket.
- Configures the bucket for static website hosting.
- Sets up an AWS CodePipeline with source, build, and deploy stages.
    
## Screenshots
### Here are some screenshots that illustrate the workflow of setting up the CICD pipeline:

### Creating an S3 Bucket
![App Screenshot](https://drive.google.com/uc?id=15s1-Idv4xzsA4GwCllDYfmJ3aecEta69)

### Uploading dist App Files to S3
![App Screenshot](https://drive.google.com/uc?id=1tazJ02QSovHlZmAE0BVQabFdlgeEdvBt)

![App Screenshot](https://drive.google.com/uc?id=1pMox7S29EhfHxijq-rdZL2pm4dW_K0Tp)

### Configuring Static Website Hosting through Bucket Policy
![App Screenshot](https://drive.google.com/uc?id=1wundXgkCWt1CGPQCk2gQMn75bndlARE3)

![App Screenshot](https://drive.google.com/uc?id=1Vle99B9aegeLvdIFvTkDwXl78MjeIT3T)

### Acceesing the frontend through Bucket Website Endpoint
![App Screenshot](https://drive.google.com/uc?id=1tykwlds0S-CPtdRYu2Y9FAn22ZpYqUg7)

### AWS CodePipeline Stages
![App Screenshot](https://drive.google.com/uc?id=1bygGgV34nQQorsthpsdKWIUiwdbklmET)

### Step 1: Choose Pipeline settings
![App Screenshot](https://drive.google.com/uc?id=1cSG_DPYvSshxNB2N2Lv1ICTcakjg5ezr)

### Step 2: Add Source stage
![App Screenshot](https://drive.google.com/uc?id=1hKWtAFiMY4BlLnyJA8nYUAOwyT27YvMp)

### Step 3: Add Build Stage
![App Screenshot](https://drive.google.com/uc?id=1C272AGPNb7pnOQXKiOrQyxe_eN5UPTRU)

![App Screenshot](https://drive.google.com/uc?id=1_a_g19Knrb4WCRv5G-oagJUMzintLTBr)

### Step 4: Add Deploy Stage
![App Screenshot](https://drive.google.com/uc?id=11kMurywkjcduXiScZqg002iR8n6Xi7eR)
