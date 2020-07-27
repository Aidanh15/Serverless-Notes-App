# Serverless-Notes-App
A siimple CRUD notes app created using AWS serverless development tools + services. Can be viewed at http://notes-app-host-bucket.s3-website-eu-west-1.amazonaws.com/

The frontend was developed with Node, Angular and express (local testing) with CI/CD managed using AWS codepipeline, alongside the trio of codecommit, codebuild and codedeploy.
The frontend connects to the REST API backend, and is served statically using a public S3 bucket, with endpoint distributution handled via AWS CloudFront. 

The backend is connected via an APIGateway managed REST API,
with note CRUD procedures handled using AWS Lambda functions in conjunction with DynamoDB for note storage and API gateway for request handling.

The project was undertaken to gain an understanding of the applications and procedures involved in AWS's serverless computing offering 
and how developers may leverage the cloud to create dynamic applications at scale.
