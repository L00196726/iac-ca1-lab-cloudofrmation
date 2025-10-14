# IaC for DevOps Pipelines - CA1 Lab Cloudformation
## Introduction
This repo is intended to host the `CA1 Lab Cloudformation` for the `IaC for DevOps Pipelines` module of the `Postgraduate Diploma in DevOps` course at `Atlantic Technological University Donegal` 
It was produced by student `L00196726 - Matheus Maximo de Araujo`
It is the Cloudformation definitions to create a RESTFull API backed by a Lambda function and a DynamoDB database.

## How to deploy
1. Make sure your AWS CLI is correctly connected to your AWS account
2. Run this command:
```
aws cloudformation deploy \
  --template restfull_app.yml \
  --stack-name restapi-cloudformation --capabilities CAPABILITY_IAM
```
