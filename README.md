# ISEC6000-assignment1-task2
# Task 2: Microservices Architecture and Deployment

## Overview

This repository contains the documentation and configuration steps for Task 2 of the ISEC6000 Secure DevOps project. Task 2 focuses on setting up a microservices architecture using Saleor Platform and deploying them on a Linux server.

## Table of Contents

- Task Overview
- Getting Started
- Setting Up Microservices
- Customizing the Compose File
- Verifying Service Launch
- Committing and Pushing Changes


## Task Overview

Task 2 involves the following key steps:

1. Acquainting ourself with the Saleor Platform.

2. Creating a personal GitHub account and forking the Saleor Platform repository.

3. Following the guidelines provided in the Saleor Platform repository to set up a Saleor stack enriched with sample data.

4. Tailoring the Docker Compose file to ensure optimal functionality, including configuring port for the Saleor Dashboard.

5. Committing the modifications and pushing them to the forked repository with the tag "isec6000-assignment1."

## Getting Started
we need to make sure we have the following prerequisites in place:
- A Linux server where you plan to deploy the Saleor stack.
- Docker and Docker Compose installed on the server.
- A GitHub account

## Setting Up Microservices

1. Familiarize yourself with the Saleor Platform:
   - Saleor Platform: Access the repository at https://github.com/saleor/saleor-platform, which contains Docker Compose elements for configuring and running Saleor components.

2. Create a personal GitHub account if you don't have one.

3. Fork the Saleor Platform repository to your GitHub account.

## Customizing the Compose File

1. Configure the Docker Compose file to customize the Saleor stack:
   - Assign port 9003 for the Saleor Dashboard.

## Verifying Service Launch

1. Initiate the Saleor platform by running the following Docker Compose command:
   docker-compose up
2. Trying localhost:9003 on our browser to verify our changes.

## Commiting and Pushing Changes.
1. Use the command "git tag isec6000-assignment1-task2" and push it using "git push origin isec-assignment1-task2"
