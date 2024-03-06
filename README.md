# Serverless Employee Profile Management System

This project implements a serverless Employee Profile Management System using various AWS services. The architecture includes:

- **User Interaction**: Users interact with the application through a web interface hosted on a CloudFront distribution.

- **Static Content Hosting**: The static content, including HTML, CSS, and JavaScript files, is hosted on an Amazon S3 bucket.

- **API Gateway**: API Gateway provides endpoints for interacting with the backend services.

- **AWS Lambda Functions**: AWS Lambda functions handle the business logic and data processing. There are two Lambda functions:

  - `SaveProfile`: Handles POST requests to save employee profiles to DynamoDB.
  - `GetProfiles`: Handles GET requests to retrieve employee profiles from DynamoDB.

- **DynamoDB**: DynamoDB is used as the database to store employee profiles.

![diagram-export-3-6-2024-10_56_59-PM](https://github.com/swwapnil777/serverless-website-hosting/assets/108779988/2c2507ab-b44a-46c0-8b9b-017866ef0090)
