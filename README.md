# Serverless TODO app
# Project 5 final course Cloud Developer 

Base on project 4 (Serverless TODO app), continue develop some feature
- containerized in Frontend with Docker
- have public docker images for Frontend
- CI/CD backend side with Travis CI


To implement this project, you need to implement a simple TODO application using AWS Lambda and Serverless framework. 
# Functionality of the application

This application will allow creating/removing/updating/fetching TODO items. Each TODO item can optionally have an attachment image. Each user only has access to TODO items that he/she has created.

# TODO items

The application should store TODO items, and each TODO item contains the following fields:

* `todoId` (string) - a unique id for an item
* `createdAt` (string) - date and time when an item was created
* `name` (string) - name of a TODO item (e.g. "Change a light bulb")
* `dueDate` (string) - date and time by which an item should be completed
* `done` (boolean) - true if an item was completed, false otherwise
* `attachmentUrl` (string) (optional) - a URL pointing to an image attached to a TODO item

You might also store an id of a user who created a TODO item.

## Setup
* nodejs >=12.
* npm install -g serverless@2.21.1
  * Backend: control by some AWS services (API Gateway, Lambda function, DynamoDB)
  * Frontend: 
    * `cd /client`
    * `npm run start`

# Deployment 
  CICD with Travis-CI for backend side
  

# Cover with project rubrics Capstone Project
  * (Option 1): Container
  * (Option 2): Functionality
  * (Option 2):Best practices
  * (Option 2):Architecture