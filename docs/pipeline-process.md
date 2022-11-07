# Pipeline Process

The piple line process has 2 main stages:

1. Build
2. Deploy

note: `Build` stage is required to start `Deploy` stage

## 1. Build
It includes serveral steps:
  - install dependencies in both frontend and api
  - lint the frontend app
  - build both frontend and api

## 2. Deploy
It also includes serveral steps:
  - install node
  - setup eb and aws/cli
  - deploy both frontend and api