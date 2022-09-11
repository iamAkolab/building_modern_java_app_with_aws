# Building Modern Java Application with AW

In the exercises, you will start by installing and configuring the AWS CLI, installing the AWS SDK, exploring the source code, and setting up AWS resources that the application will use. A frontend website (that you can use to interact with the backend API) is provided.

Then, you will begin to build the backend API with Amazon API Gateway, add authentication to that API, create the backend compute functions with AWS Lambda, and create an asynchronous workflow with AWS Step Functions. You will also implement distributed tracing with AWS X-Ray, use monitoring features, and improve performance for the distributed application.

AWS services used:
* Amazon Simple Storage Service (Amazon S3)
* Amazon API Gateway
* Amazon Cognito
* AWS Lambda
* AWS Step Functions
* AWS X-Ray
* AWS Systems Manager Parameter Store.

## Exercise
* Exercise 1: You will install and configure the AWS CLI and the AWS SDK. Then, you will create an S3 bucket and deploy a web application to the bucket. Finally, you will set up data in Amazon S3, and configure AWS Systems Manager parameters for the Dragons application.

* Exercise 2: You will set up a mock backend API by using Amazon API Gateway REST APIs. You will then set up three API endpoints, which will respond to requests with mocked data. As a final step, you will test the mock API.

* Exercise 3: You will secure the API that you built in Lab 2 by adding authentication through Amazon Cognito user pools.

* Exercise 4: You will create Lambda functions to host the backend for your API. Then, you will configure the secured API that you built in Lab 3 so that it invokes the Lambda functions instead of the mock integrations.

* Exercise 5: You will create an asynchronous state machine with AWS Step Functions to orchestrate the add dragon feature of the API. You will then configure the API to run this state machine when a request reaches an API endpoint that you built in the previous labs.

* Exercise 6: You will use X-Ray to trace requests through your distributed application. You will also make improvements to your application by using various AWS service features.


