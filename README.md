# Celebgram
This is for demonstrating AWS Step Functions with SDK integrations!

In this demo, the [SAM Template](./template.yaml) shows how the State Machines could use SDK integrations with Amazon Rekognition and Amazon DynamoDB to create Serverless orchestration of Recognizing a celebrity from an image uploaded to S3.

You can read more about it in my blog-post - https://dev.to/aws-builders/why-aws-step-functions-and-sdk-integrations-4eeh

This was presented at AWS APAC Community Summit '22, Bangkok. You can view the [slide-deck](https://speakerdeck.com/zachjonesnoel/build-better-with-step-functions-and-sdk-integrations).

# How to try it?

Clone the project 

With [AWS SAM](https://aws.amazon.com/serverless/sam/) CLI pre-installed, build the SAM app with 
```
sam build
```

Deploy to your AWS Account with 
```
sam deploy --guided
```

Once you have tried it out, don't forget to delete with 
```
sam delete
```
