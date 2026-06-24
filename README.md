# Serverless-Employee-Management-API-on-AWS

## What the project is
The Serverless Employee Management System is a cloud-native web application built on AWS that enables users to manage employee records through Create, Read, Update, and Delete (CRUD) operations.
The application leverages AWS serverless services to provide a scalable, highly available, and low-maintenance architecture without the need to manage servers.

## Architecture

[![Architecture Diagram](/docs/images/serverless-architechture.png)](/docs/images/serverless-architechture.png)

## Features
1. Create employee records
2. View employee details
3. Update existing employee information
4. Delete employee records
5. Serverless backend architecture
6. Static website hosting using Amazon S3
7. RESTful API integration using API Gateway
8. NoSQL data storage using DynamoDB
8. Secure AWS service communication through IAM roles

## API Endpoints
| Method | Endpoint | Description |
|---------|-----------|-------------|
| POST | `/employee` | Create Employee |
| GET | `/employees` | Get All Employees |
| PUT | `/employee/{employeeId}` | Update Employee |
| DELETE | `/employee/{employeeId}` | Delete Employee |

## Screenshots / Demo
| Home Page                                                                                                         | API Gateway                                                                                                     |
| ----------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------ |
| [![Screenshot of form homepage](/docs/images/employee-form-home-page.png)](docs/images/employee-form-home-page.png) | [![Screenshot of API Gateway screen](/docs/images/)](/docs/images/)

## Learning Outcomes
- Serverless Application Development
- AWS Lambda
- API Gateway Integrations
- DynamoDB Operations
- IAM Roles and Permissions
- S3 Static Website Hosting
- REST API Design
- Frontend and Backend Integration