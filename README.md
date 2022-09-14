# Celebgram
This is for demonstrating AWS Step Functions with SDK integrations!

In this demo, the [SAM Template](./template.yaml) shows how the State Machines could use SDK integrations with Amazon Rekognition and Amazon DynamoDB to create Serverless orchestration of Recognizing a celebrity from an image uploaded to S3.

#How to try it?
Clone the project 
```
```

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