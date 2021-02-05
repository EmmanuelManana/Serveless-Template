- read serverless.com docs on how to configure sls to work AWS
- npm install -g serverless
- serverless create --template aws-nodejs --name "my-special-service"
- sls deploy -v or sls dpeloy
- help, sls --help or sls -h

<!-- create a fnction through mocha -->
serverless create function -f testFunction --handler src/functions/testFunction.testFunction --path src/tests/


<!-- how to use -->
serverless create --template-path "where you cloned this repo" --path "the service you want to create"