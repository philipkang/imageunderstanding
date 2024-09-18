# imageunderstanding
Amazon Lambda code use bedrock converse API invoking Bedrock Claude 3.5 sonnet for multimodal image understanding

Contents:

1.  Lambda Function code
2.  Lambda Layer zip
3.  Deploy Steps
    -  Deploy Lambda Function "imageUClaude35" with "boto3install.zip" layer
    -  Create an AWS API Gateway trigger the Lambda function
    -  The REST API endpoint will be invoked in your web application anytime to send the images for LLM understanding
