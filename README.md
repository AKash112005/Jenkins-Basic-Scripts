Jenkins Pipeline Script Demo
Project Overview

      This project demonstrates a basic Jenkins Pipeline setup that pulls code from a Git repository and executes pipeline stages. The pipeline script is written to verify Jenkins integration with a repository and to test both Declarative and Scripted Pipeline styles.
      
      The repository contains sample code and pipeline scripts used to validate the Jenkins build process .

Objectives

    Configure Jenkins to connect with a Git repository.
    
    Execute pipeline scripts using Jenkins.
    
    Test both Declarative Pipeline and Scripted Pipeline approaches.
    
    Understand Jenkins build stages and automation workflow.

Tools & Technologies

    Jenkins
    
    Git / GitHub
    
    Pipeline Script (Groovy)
    
    CI/CD Concepts

Repository Structure
        jenkins-pipeline-demo/
        │
        ├── Jenkinsfile-declarative
        ├── Jenkinsfile-scripted
        ├── sample-code/
        │   └── example files
        └── README.md
Pipeline Types Implemented
  1. Declarative Pipeline
    
      Declarative pipeline uses a structured syntax and is easier to read and maintain.
      
      Example stages included:
      
      Checkout code from repository
      
      Build stage
      
      Test stage
      
      Deployment simulation

2. Scripted Pipeline

      Scripted pipeline provides more flexibility using Groovy scripting.
      
      Example stages included:
      
      Node execution
      
      Git checkout
      
      Build execution
      
      Output logging
      
      Jenkins Pipeline Workflow
      
      Jenkins job is created.
      
      Repository URL is configured in Jenkins.
      
      Jenkins pulls the pipeline script from the repository.
      
      Pipeline stages are executed sequentially.
      
      Build results are displayed in Jenkins dashboard.
    
How to Run the Pipeline
    
      Install Jenkins.
      
      Install required plugins:
      
      Git Plugin
      
      Pipeline Plugin
      
      Create a New Pipeline Job in Jenkins.
      
      Configure the Git repository URL.
      
      Set Pipeline script from SCM.
      
      Select the branch and Jenkinsfile.
      
      Run Build Now.

Expected Output

    Jenkins successfully clones the repository.
    
    Pipeline stages execute in order.
    
    Console output shows build logs and execution status.

Learning Outcome

    Understanding of Jenkins pipeline configuration.
    
    Experience with both declarative and scripted pipelines.
    
    Basic CI/CD workflow implementation.
    

    
