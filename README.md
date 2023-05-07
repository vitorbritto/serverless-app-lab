# Serverless Lab App

## Built with:
- Static Web Page
- API Gateway
- Lambda Function
- DynamoDB

## Steps:
1. The Static Webpage send a request to the API Gateway usgin the value "fullName" from the form
2. The API Gateway connects with the Lambda Function
3. The Lambda Function triggers the DynamoDB and put the item into it
4. The DynamoDB receives this data
5. The Lambda sends back the result for the API Gateway  
6. The API Gateway finish the request cycle sending the result for the Static Web Page (via console log on this experimental project)