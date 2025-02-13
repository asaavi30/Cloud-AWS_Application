# Cloud-integrated Engineering Calculator

This project is a fully functional Engineering Calculator that performs both arithmetic and scientific calculations. The frontend is built using HTML, CSS, and JavaScript, while the backend leverages AWS services for computation and data storage. The website is hosted on Vercel for seamless accessibility.

## Amazon Web Services Used

* AWS API Gateway: Routes HTTP requests to the Lambda function.
* AWS Lambda: Executes serverless code for arithmetic and scientific calculations.
* AWS DynamoDB: A NoSQL database used to store and retrieve calculation results.
* AWS IAM: Manages permissions and access control across AWS services.
* Vercel: Hosting

## Project Workflow

* Frontend: Users input numbers and select operations via the web interface.
* API Gateway: HTTP requests from the frontend are routed to the Lambda function.
* Lambda Function: Performs the requested calculations (e.g., addition, subtraction, logarithms, permutations, etc.).
* DynamoDB: Stores calculation results for future retrieval.
* IAM: Ensures secure and controlled access to AWS resources.

## Deployment
Vercel hosting link: https://cloud-1esbdghlq-riyan1806.vercel.app/
