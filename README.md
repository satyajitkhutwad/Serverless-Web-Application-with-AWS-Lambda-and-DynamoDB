# Serverless-Web-Application-with-AWS-Lambda-and-DynamoDB
### Objectives
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
####Challenges faced.
I faced access-denied issues until I gave appropriate IAM privileges to the Lambda function for accessing DynamoDB.
Also, while testing the API through the browser, I encountered errors until I enabled CORS in the API Gateway.
Moreover, getting used to the NoSQL nature of MongoDB was a challenge at first but turned out to be very convenient while implementing the CRUD operations.

####Learnings
This assignment helped me learn to work with serverless backends with the help of API Gateways and Lambda functions in AWS. It also gave me a fair understanding of various configurations and IAM privileges required for connecting your services to DynamoDB. Understanding how to implement CRUD operations on a NoSQL database was the highlight for me. The serverless nature of Lambda and the scalability that it offers are the two important learnings for me in this assignment.
