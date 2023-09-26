## SERVERLESS PIPELINE USING AWS CDK AND LAMBDA IN PYTHON

In this project, we will create a serverless pipeline using AWS CDK (Cloud Development Kit) and Lambda in Python. As a part of this simple project, we will create a simple pipeline that triggers a Lambda function 
when a change is made to a specific S3 bucket. So, this pipeline will use AWS CDK to define and deploy the necessary infrastructure.

Before we proceed, make sure that you have the AWS CDK installed and configured on your system. You'll also need to have Python and Node.js installed. Since this is a beginner-friendly project, let us understand 
"How to get started with AWS CDK" and install some prerequisites for the project.



## GETTING STARTED WITH AWS CDK"
CDK (Cloud Development Kit) is a framework for defining cloud infrastructure in code and provisioning it through Cloud Formation templates. You can connect your AWS resources together (even across Stacks) and grant
permissions using simple, intent-oriented API's. In short, it is defined as "cloud infrastructure as code", i.e., provisioning cloud infrastructure using programming languages. CDK supports: TypeScript, JavaScript,
Python, Java, C#/.Net, and Go languages
For more information and documentation about CDK, refer to: https://docs.aws.amazon.com/cdk/v2/guide/home.html

Getting started with AWS CDK includes the following steps:

# STEP 1: PREREQUISITES

Before you begin, make sure you have the following prerequisites in place:

An AWS account: You'll need an AWS account to use AWS CDK.

AWS CLI: Install the AWS Command Line Interface (CLI) and configure it with your AWS credentials. You can download and install it from the AWS CLI website: https://aws.amazon.com/cli/

Node.js and npm: AWS CDK uses Node.js for its CLI. You can download Node.js from the official website: https://nodejs.org/

## STEP 2 : Install AWS CDK

Open a terminal or command prompt and install AWS CDK globally using npm:
````bash
npm install -g aws-cdk
```









