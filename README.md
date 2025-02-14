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

## Steps
* Step 1: The frontend code was deployed using Vercel for building and hosting the webpage. Vercel provides a fast and reliable platform for hosting static websites.
* Step 2: Created a new Lambda function using the Python 3.9 runtime.
* Step 3: Replaced the default code with custom logic to perform calculations (e.g., addition, subtraction, logarithms, permutations, etc.). Used the math library in Python for advanced calculations. Tested the function using configured test events to ensure accurate results.
* Step 4: Created a REST API and configured a POST method to invoke the Lambda function. Enabled CORS (Cross-Origin Resource Sharing) to allow frontend communication. Deployed the API to a dev stage and obtained the invoke URL.
* Step 5: AWS DynamoDB was used to store and retrieve calculation results. Created a new table with a partition key to store calculation results. Copied the table’s ARN (Amazon Resource Name) for use in IAM policies. AWS IAM was used to grant the Lambda function permissions to access DynamoDB.
* Step 6: Created an inline policy to allow PutItem, GetItem, Scan, and other DynamoDB actions. Attached the policy to the Lambda function’s execution role.
* Step 7: Updated the Lambda function code to write calculation results to DynamoDB. Verified that results were successfully stored in the DynamoDB table.

## Screenshots

### Frontend Interface
![](screenshots/1.png)

### Lambda function
![](screenshots/2.png)
![](screenshots/3.png)
![](screenshots/4.png)

### Configure Test Event
![](screenshots/5.png)
![](screenshots/6.png)
![](screenshots/7.png)
![](screenshots/8.png)

### Create Rest API
![](screenshots/9.png)
![](screenshots/10.png)
![](screenshots/11.png)
![](screenshots/12.png)

### Create POST method
![](screenshots/13.png)
![](screenshots/14.png)
![](screenshots/15.png)
![](screenshots/17.png)
![](screenshots/18.png)
![](screenshots/19.png)

### Enable CORS (Cross-Origin Resource Sharing)
![](screenshots/20.png)
![](screenshots/21.png)
![](screenshots/22.png)

### Deploy API
![](screenshots/23.png)
![](screenshots/24.png)
![](screenshots/25.png)
![](screenshots/26.png)
![](screenshots/27.png)
![](screenshots/28.png)
![](screenshots/29.png)
![](screenshots/30.png)

### DynamoDB
![](screenshots/31.png)
![](screenshots/32.png)
![](screenshots/33.png)
![](screenshots/34.png)
![](screenshots/35.png)
![](screenshots/36.png)
![](screenshots/37.png)
![](screenshots/38.png)

### IAM (Identity and Access Management)
![](screenshots/39.png)
![](screenshots/40.png)
![](screenshots/41.png)
![](screenshots/42.png)
![](screenshots/43.png)
![](screenshots/44.png)
![](screenshots/45.png)
![](screenshots/46.png)
![](screenshots/47.png)
![](screenshots/48.png)
![](screenshots/49.png)
![](screenshots/50.png)

### Explore Table Items
![](screenshots/51.png)
![](screenshots/52.png)

### Result implementation using mutilication operator
![](screenshots/53.png)










