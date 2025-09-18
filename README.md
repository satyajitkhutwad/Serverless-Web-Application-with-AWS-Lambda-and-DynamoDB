# Serverless-Web-Application-with-AWS-Lambda-and-DynamoDB

1. Trigger a Lambda function using an API Gateway.
2. Interact with DynamoDB to perform basic CRUD operations.
3. Deploy and test the application in the AWS environment.

### API Gateway
![screenshot](/Screenshots/api_gateway.png)

### Performing CRUD operations using API Gateway to triggering the Lambda
![screenshot](/Screenshots/curl_output1.png)

![screenshot](/Screenshots/curl_output2.png)

### Populated DynamoDB table
![screenshot](/Screenshots/populated_table.png)


### Reflections
#### Challenges Faced
I faced access-denied issues until I granted appropriate IAM permissions to the Lambda function for accessing DynamoDB.
While testing the API through the browser, I encountered errors until I enabled CORS in API Gateway.
Moreover, getting used to the NoSQL nature of DynamoDB was a challenge at first, but it turned out to be very convenient when implementing CRUD operations.

#### Learnings
This assignment helped me learn to work with serverless backends using API Gateway and AWS Lambda.
It also gave me a solid understanding of the configurations and IAM privileges required to connect services to DynamoDB.
Implementing CRUD operations on a NoSQL database was the highlight for me.
The serverless model of Lambda and the scalability it offers were two important lessons from this assignment.
