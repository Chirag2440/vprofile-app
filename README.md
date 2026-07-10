# vProfile Application

## Overview

This repository contains the application source code and the Continuous Integration (CI) pipeline responsible for building, testing, analyzing, and containerizing the application.

## Technologies Used

- GitHub
- Jenkins
- Maven
- SonarQube
- Docker
- Amazon ECR

## Workflow

1. Push source code to GitHub.
2. Jenkins triggers the CI pipeline.
3. Maven builds the application.
4. SonarQube analyzes code quality.
5. Docker builds the application image.
6. Docker pushes the image to Amazon ECR.
7. Jenkins updates the Helm image tag.

## Key Features

- Automated CI pipeline
- Maven build automation
- SonarQube integration
- Docker image creation
- Amazon ECR image publishing

## Learning Outcomes

- Built an automated CI workflow.
- Integrated code quality checks.
- Managed Docker images with Amazon ECR.