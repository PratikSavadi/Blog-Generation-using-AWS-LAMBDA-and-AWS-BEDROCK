# Blog Generation using AWS Cloud BEDROCK and LAMBDA and API GATEWAY

In this example, we'll create a Lambda function that connects different LLM model from AWS BEDROCK.
Using POSTMAN we will call api gateway from AWS which is intergated with Lambda function

### Description:

The Lambda function takes the input from user to generate blog.It also calls the relevent LLM model from AWS BEDROCK.It also calls the S3 bucket where the blog is stored as text file.Then we craeted the API using AWS API GATEWAY where the lambda function is integrated.The API is called it from POSTMAN APP where blog topic is 
also given as input.

STEPS

1. Create lambda function
2. Acess the LLM model from BEDROCK which can work as blog generation we have used meta llama3-70b-instruct-v1:0
3. Create a API GATEWAY to connect with POSTMAN
4. Integrate AWS LAMBDA to API GATEWAY
5. Create S3 bucket to save blog generation to text file
6. Call the API using postman app where you can give blog generation
7. Logs will visible in Cloud Watch
