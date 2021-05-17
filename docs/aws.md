# :rocket: Awesome AWS :rocket:

A list of resources for all things AWS.

## General Architecture

### Vidoes

* [Building with AWS Databases: Match Your Workload to the Right Database](https://www.youtube.com/watch?v=hwnNbLXN4vA) - 50 minute presentation from re:Invent 2018 that discusses picking the right type of database (e.g. relational, NoSQL, Graph) for your workload 

## API Gateway

### Documentation

* [Integration subtype reference](https://docs.aws.amazon.com/apigateway/latest/developerguide/http-api-develop-integrations-aws-services-reference.html) - Reference for integrating an HTTP API route with an AWS service list EventBridge or SQS.

## DynamoDB

### Videos

* [Data modeling with Amazon DynamoDB](https://www.youtube.com/watch?v=DIQVJqiSUkE) - 40 minute introduction to DynamoDB from re:Invent 2019.
* [Amazon DynamoDB deep dive: Advanced design patterns](https://www.youtube.com/watch?v=6yqfmXiZTlM) - 60 minute deep dive into modeling complex relationships in DynamoDB from re:Invent 2019

## EventBridge

### Blogs

* [Building Salesforce integrations with Amazon EventBridge and Amazon AppFlow](https://aws.amazon.com/blogs/compute/building-salesforce-integrations-with-amazon-eventbridge/) - Official AWS blog post that gives a step-by-step overview of handling a Salesforce event with an AWS Lambda function using AppFlow and EventBridge.

### Documentation

* [Amazon EventBridge permissions reference](https://docs.aws.amazon.com/eventbridge/latest/userguide/eb-permissions-reference.html) - List of the actions you can specify in an IAM policy for use with EventBridge.
* [Amazon EventBridge troubleshooting](https://docs.aws.amazon.com/eventbridge/latest/userguide/eb-troubleshooting.html) - Official troubleshooting guide.

### Videos

* [Building event-driven architectures w/ Amazon EventBridge](https://www.youtube.com/watch?v=Hih-bF8qYgU) - 50 minute presentation on implementing event driven systems using EventBridge from re:Invent 2019.
* [Deep Dive on Amazon EventBridge - AWS Online Tech Talks](https://www.youtube.com/watch?v=28B4L1fnnGM) - 50 minute demonstration of building an application using EventBridge from AWS Online Tech Talks series. Lots of code and console examples.

## S3

### Documentation

* [Actions, resources, and condition keys for Amazon S3](https://docs.aws.amazon.com/service-authorization/latest/reference/list_amazons3.html) - A list of all IAM actions that can be configured for S3. This is useful when creating IAM policies related to S3.

## SAM (Serverless Application Model)

### Documentation

* [Developer Guide](https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/what-is-sam.html) - Official documentation for SAM.

## Step Functions

### Documentation

* [Quotas](https://docs.aws.amazon.com/step-functions/latest/dg/limits-overview.html)
* [Amazon States Language](https://states-language.net/spec.html) - Describes the JSON-based for describing state machines declaratively that is used by Setp Functions.

### Blogs

* [Handling Errors, Retries, and adding Alerting to Step Function State Machine Executions](https://aws.amazon.com/blogs/developer/handling-errors-retries-and-adding-alerting-to-step-function-state-machine-executions/) - Official AWS blog post about error handling in Step Functions.

### Videos

* [Parallelism and concurrency in Step Functions and AWS Lambda](https://www.youtube.com/watch?v=At5mw8T2riY) - 35 minutes deep dive on leveraging parallelism and concurrency when running step functions.
* [JSONPath data processing](https://www.youtube.com/watch?v=QpZ6IdKvOdw) - 60 minutes video covering how to handle input and output data in Step Functions.
