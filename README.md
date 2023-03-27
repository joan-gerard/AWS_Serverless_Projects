### AWS Serverless Project Series

As I have been wanting to focus on backend, I have built 7 practical projects, each building upon the skills gained in the last project.

These projects are summarized below:

## The Projects

| Projects           | Repos                            | Description                                                 | AWS Services |
| :----------------- | :------------------------------- | :---------------------------------------------------------- | :--------: |
| combination API    | [combinationAPI](https://github.com/joan-gerard/combinationAPI_AWS_Serverless)| With the first project, I wanted to focus on learning the fundamentals, i.e. setting up a serverless project, creating an API endpoint (HTTP with API Gateway), writing my first Lambda function and deploying to AWS, all within an IDE. When called, the endpoint will trigger the Lambda, which then makes requests to two external APIs and combines results altogether.      | API Gateway
| redirect URL       | [redirectUrl](https://github.com/joan-gerard/redirectUrl_AWS_Serverless) | I wrote two Lambda functions, therefore two endpoints: The first function allows the user to POST and store a URL into a table and receive a unique code as a response. When adding that unique code to the end of the second endpoint, a user will be able to GET back the original URL. This project is very useful when wanting to create URL redirects | API Gateway, DynamoDB
| Reminder App       | [reminderApp](https://github.com/joan-gerard/reminderApp_AWS_Serverless)               |  The backend that I have built can be used to build an app which enables users to create reminders and to get notified of a reminder either via email or text message when a reminder reaches its expiry date (Time-To-Live) or is deleted.      | API Gateway, DynamoDB, Dynamo Streams, SES, SNS|
| Live Chat          | [liveChat](https://github.com/joan-gerard/liveChat_AWS_Serverless) | The main objective of this project was to learn how to create an API Gateway Websocket endpoint. The endpoint is then integrated with Lambda functions. I have built that into a messaging platform, where users can create or join an existing room, and then send messages | API Gateway, DynamoDB
| Idea Voting App    | [ideaVoting](https://github.com/joan-gerard/ideaVoting_AWS_Serverless)                  | For this project, I wanted to apply the concept of ‘single-table design’ to my Dynamo database and introduce two new Amazon products to my projects, namely Cognito and Amplify. | Dynamo DB, Cognito,  Amplify|
| E-commerce site    | [e-commerce](https://github.com/joan-gerard/ecommerceApp_AWS_Serverless)         | An e-commerce backend with an event-driven architecture using AWS EventBridge (EB)               | DynamoDB, Cognito, SNS, EventBRidge, Secrets


