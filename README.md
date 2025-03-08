# AWS API Gateway + Lambda (Serverless REST API)

This project demonstrates a serverless API using AWS API Gateway and AWS Lambda (Python 3.11).

## Features
- REST API with API Gateway
- Lambda function (Python) for GET requests
- Proxy integration with API Gateway
- CloudWatch logging for debugging
- Deployed with a Regional endpoint

## How to Use
1. Deploy the Lambda function on AWS.
2. Set up API Gateway and integrate with Lambda.
3. Deploy and test the API using the Invoke URL.

## Example Response
```json
{
  "statusCode": 200,
  "body": "Hello from Lambda"
}
