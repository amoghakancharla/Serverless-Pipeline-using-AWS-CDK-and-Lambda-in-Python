# Serverless Pipeline using AWS CDK and Lambda in Python

In this project, we will create a serverless pipeline using AWS CDK (Cloud Development Kit) and Lambda in Python. As a part of this, we will create a simple pipeline that triggers a Lambda function when a change 
is made to a specific S3 bucket. For this pipeline, we will use AWS CDK to define and deploy the infrastructure in the form of stacks.

To begin with, make sure you have the AWS CDK installed and configured on your system. Check the `gettingstartedwithcdk.md` file in this repository if you haven't.You'll also need to have Python and Node.js installed. 
Let's understand each step in detail as follows:

## Step 1: Create a New AWS CDK Project
Open a terminal and create a new AWS CDK Project as follows:
```bash
mkdir serverless-pipeline
cd serverless-pipeline
cdk init app --language=python
```
## Step 2: Install necessary CDK and AWS SDK libraries
The next step includes installing necessary CDK and AWS SDK libraries required for the project
```bash
pip install aws-cdk.core aws-cdk.aws-s3 aws-cdk.aws-lambda aws-cdk.aws-events aws-cdk.aws-events-targets
```
## Step 3: Define the CDK Stack
In this, we'll be using Python to define and deploy the stack to AWS.The code used to define the stack in this project is included in the `CDK-stack` file of this repository.
In your project directory, open the `serverless_pipeline/serverless_pipeline_stack.py` file and define the stack.

## Step 4: Create the Lambda function
In the root of your project directory, create a folder named `lambda`. Inside this folder, create a `lambda.py` file and define the Lambda function using Python.

## Step 5: Deploy the CDK Stack
Deploy the Stack by running
```bash
cdk deploy
```
## Step 6: Testing the Pipeline
Upload a file to the S3 bucket you created earlier using the Stack, and you should see the Lambda function being triggered by the S3 event.

This created a simple serverless pipeline using AWS CDK and Lambda in Python. You can expand upon this example by adding more stages to your pipeline or integrating with other AWS services as needed
for your specific use case.
