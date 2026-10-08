# CI/CD Pipeline Automation Using GitHub Actions, Tekton, and OpenShift

## Project Overview

This project demonstrates the implementation of an automated Continuous Integration and Continuous Delivery (CI/CD) pipeline using GitHub Actions, Tekton, and Red Hat OpenShift. The pipeline automates code quality checks, unit testing, container image building, and application deployment.

## Objectives

* Create a CI pipeline using GitHub Actions for linting and unit testing.
* Define reusable Tekton tasks for linting, unit testing, and building container images.
* Create an OpenShift CI pipeline using the previously defined Tekton tasks.
* Integrate a deployment stage to deploy the application to an OpenShift cluster.
* Automate the software delivery workflow to improve consistency and reliability.

## Technologies Used

* **GitHub Actions** — CI workflow automation
* **Tekton** — Kubernetes-native CI/CD pipelines and tasks
* **Red Hat OpenShift** — Container application platform
* **Docker** — Container image building
* **Kubernetes** — Container orchestration
* **Git and GitHub** — Version control and source code management

## Project Workflow

1. **Source Code Management:** Store and manage application source code in GitHub.
2. **Linting:** Check source code for style issues and potential errors.
3. **Unit Testing:** Execute unit tests to validate application functionality.
4. **Image Building:** Build a container image using Tekton tasks.
5. **Pipeline Integration:** Combine the tasks into an OpenShift CI pipeline.
6. **Deployment:** Deploy the application to the lab's OpenShift cluster.

## Implementation

### 1. GitHub Actions

Configure a GitHub Actions workflow to automate linting and unit testing whenever code changes are pushed or a pull request is created.

### 2. Tekton Tasks

Create reusable Tekton tasks for:

* Source code linting
* Unit testing
* Container image building

### 3. OpenShift CI Pipeline

Integrate the Tekton tasks into an OpenShift pipeline to execute the CI stages in the required order.

### 4. Application Deployment

Add a deployment stage to the OpenShift pipeline to deploy the application to the lab OpenShift cluster.

## Expected Outcomes

* Automated linting and unit testing
* Repeatable container image builds
* Integrated CI/CD workflow
* Automated application deployment to OpenShift
* Improved consistency and traceability of software releases

## Learning Outcomes

This project provides practical experience with CI/CD automation, GitHub Actions workflows, Tekton tasks and pipelines, containerization, and Kubernetes-based application deployment using Red Hat OpenShift.

## Project Status

Developed as part of the Coursera CI/CD course final project using the IBM Skills Network Labs environment.
