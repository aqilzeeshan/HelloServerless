node -v

v14.15.4

npm -v
7.4.2

aws --version
aws-cli/1.18.216 Python/3.9.1 Windows/10 botocore/1.19.56

serverless --version
Framework Core: 2.19.0
Plugin: 4.4.2
SDK: 2.3.2
Components: 3.4.7

sls invoke -f hello
{
    "statusCode": 200,
    "body": "{\n  \"message\": \"Go Serverless v1.0! Your function executed successfully!\",\n  \"input\": {}\n}"
}
