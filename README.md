# Jenkins Pipeline Notes 🚀

## What is Jenkins Pipeline?
A Jenkins Pipeline is a set of automated steps to build, test, and deploy code.

## Basic Declarative Pipeline

```groovy
pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building the application...'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying to server...'
            }
        }
    }
}
```

## Pipeline Stages Explained

- **agent any** — Run the pipeline on any available Jenkins agent
- **stage('Build')** — Compile the source code
- **stage('Test')** — Run automated tests
- **stage('Deploy')** — Deploy application to the server
