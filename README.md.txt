# Student Serverless API

## Project Overview
This project is a serverless REST API built using AWS services.
It stores student information in DynamoDB using AWS Lambda and API Gateway.

## Technologies Used
- AWS Lambda (Python)
- Amazon API Gateway
- Amazon DynamoDB
- Postman

## Architecture
Client (Postman) → API Gateway → Lambda → DynamoDB

## API Details
Method: POST  
Endpoint: /student-handler

## Sample Request
```json
{
  "student_id": "4001",
  "name": "Suresh",
  "department": "CSE",
  "year": 3
}

## Sample Response

```json
"Student added successfully"

