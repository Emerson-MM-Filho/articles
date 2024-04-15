# Continuous Integration and Continuous Deployment (CI/CD) Manual

> "anyone should be able to bring in a virgin machine, check the sources out of the repository, issue a single command, and have a running system on their machine." - Martin Fowler (2006), [Continuous Integration](https://martinfowler.com/articles/continuousIntegration.html)

## Introduction

This manual is intended to provide a guide to the CI/CD process for the project. It will cover the following topics:

* [CI/CD Overview](#cicd-overview)
* [CI/CD Pipeline](#cicd-pipeline)
* [CI/CD Tools](#cicd-tools)
* [CI/CD Process](#cicd-process)
* [CI/CD Configuration](#cicd-configuration)
* [CI/CD Troubleshooting](#cicd-troubleshooting)

## CI/CD Overview

Continuous Integration and Continuous Deployment (CI/CD) is a software development practice where members of a team integrate their work frequently, usually each person integrates at least daily - leading to multiple integrations per day. Each integration is verified by an automated build (including test) to detect integration errors as quickly as possible. Many teams find that this approach leads to significantly reduced integration problems and allows a team to develop cohesive software more rapidly.

## CI/CD Pipeline

The CI/CD pipeline is a sequence of steps that run the CI/CD process. The following diagram shows the CI/CD pipeline:

[![CI/CD Pipeline](images/cicd-pipeline.png 'CI/CD Pipeline Diagram')](https://chayanit-chaisri.medium.com/ci-cd-pipeline-fcd43be04467)


## CI/CD Tools

The following tools are used for the CI/CD process:

* [Git](https://git-scm.com/) - Version control system.
* [Bitbucket](https://bitbucket.org/) - Git repository hosting service.
* [Bitbucket Pipelines](https://bitbucket.org/product/features/pipelines) - Continuous integration and delivery built into Bitbucket.
* [Docker](https://www.docker.com/) - Container platform.

## CI/CD Process

The CI/CD process is a sequence of steps that run the CI/CD pipeline. The following diagram shows the CI/CD process:

![CI/CD Process](images/cicd-process.png)

The following steps are performed by the CI/CD process:

1. A developer pushes code changes to the Bitbucket repository.
2. Bitbucket Pipelines detects the code changes and starts the CI/CD pipeline.
3. Bitbucket Pipelines builds the Docker image.
4. Bitbucket Pipelines pushes the Docker image to the Docker registry.
5. Bitbucket Pipelines deploys the Docker image to the development environment.
6. Bitbucket Pipelines deploys the Docker image to the staging environment.
7. Bitbucket Pipelines deploys the Docker image to the production environment.

## CI/CD Configuration

The CI/CD configuration is a sequence of steps that configure the CI/CD process. The following diagram shows the CI/CD configuration:

![CI/CD Configuration](images/cicd-configuration.png)

The following steps are performed by the CI/CD configuration:

1. Create a Docker image of the application.
2. Push the Docker image to a Docker registry.
3. Deploy the Docker image to the development environment.
4. Deploy the Docker image to the staging environment.
5. Deploy the Docker image to the production environment.

## CI/CD Troubleshooting

The following tools can be used to troubleshoot the CI/CD process:

* [Bitbucket Pipelines](https://bitbucket.org/product/features/pipelines) - Continuous integration and delivery built into Bitbucket.
* [Docker](https://www.docker.com/) - Container platform.
* [Kubernetes](https://kubernetes.io/) - Production-grade container orchestration system.

## References

Check out the [References](references.md) for more information.