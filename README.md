# Hosting a Full-Stack Application

## About

This task is to host a full-stack application on a cloud provider. The application is built using the Node.js for the backend and Angular for the frontend. The application is hosted on a cloud provider (AWS), and the CI/CD pipeline is implemented using CircleCI. The application is deployed on a Elastic Beanstalk, S3 Bucket and RDS on AWS.

## Technologies Used

- Node.js
- Angular
- AWS (Elastic Beanstalk, S3 Bucket, RDS)
- CircleCI

## CI/CD Pipeline

- The CI/CD pipeline is implemented using CircleCI. The pipeline is triggered when a new commit is pushed to the repository. The pipeline consists of the following steps:
  - Install dependencies
  - Build the Angular application
  - Run the unit tests
  - Deploy the application to Elastic Beanstalk

### Build Pipeline

- Pull node.js image from docker
- Install node.js and checkout code
- Install dependencies in the frontend app
- Install dependencies in the backend API
- Lint the frontend code
- Build the frontend app
- Build the backend API

### Deploy Pipeline

- Pull node.js image from docker
- Install node.js, eb/setup, aws-cli/setup and checkout code
- Run the deploy command

## Steps to Host the Application

- Clone the repository
- Create a new Elastic Beanstalk application
- Create a new RDS instance
- Create a new S3 bucket
- Update the environment variables in the Elastic Beanstalk application
- Update the environment variables in the Angular application
- Push the changes to the repository
- The CI/CD pipeline will be triggered and the application will be deployed to Elastic Beanstalk
