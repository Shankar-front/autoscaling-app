## Architecture Diagram

![Serverless Architecture](architecture.png)

## End-to-End Pipeline Flow
1. Client sends HTTPS POST request to API Gateway
2. API Gateway invokes AWS Lambda function
3. Lambda processes request and stores data in DynamoDB
4. CloudWatch captures logs and metrics
