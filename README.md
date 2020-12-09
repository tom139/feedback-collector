# Feedback Collector

Feedback Collector is an AWS Serverless App that allows to quickly integrate a mechanism for collecting user feedbacks.

## How it works

Feedback Collector deploys a fully serverless application on AWS exposing some public API to receive feedbacks, those feedbacks are saved in a DynamoDB table and a workflow is triggered to notify people from your organization in charge of respond to user feedback to act.
