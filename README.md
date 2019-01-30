This project is a serverless example showing how to create a GET method using Amazon API Gateway, Lambda, and NodeJS.

Amazon API Gateway
  /hello
    GET

AWS Lambda
  aws-env-with-lambda-1-dev-hello


Service Information
service: aws-env-with-lambda-1
stage: dev
region: us-east-1
stack: aws-env-with-lambda-1-dev
api keys:
  None
endpoints:
  GET - https://abc123.execute-api.us-east-1.amazonaws.com/dev/hello
functions:
  hello: aws-env-with-lambda-1-dev-hello
layers:
  None

Stack Outputs
HelloLambdaFunctionQualifiedArn: arn:aws:lambda:us-east-1:559681517647:function:aws-env-with-lambda-1-dev-hello:2
ServiceEndpoint: https://abc123.execute-api.us-east-1.amazonaws.com/dev
ServerlessDeploymentBucketName: aws-env-with-lambda-1-de-serverlessdeploymentbuck-9sn51acp6phz



