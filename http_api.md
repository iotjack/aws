HTTP APIs is at least 71% lower cost compared to API Gateway REST APIs.

[https://aws.amazon.com/blogs/compute/building-better-apis-http-apis-now-generally-available/](https://aws.amazon.com/blogs/compute/building-better-apis-http-apis-now-generally-available/)

[HTTP APIs vs REST APIs](https://docs.aws.amazon.com/apigateway/latest/developerguide/http-api-vs-rest.html)

## Use
* You can use HTTP APIs to send requests to AWS Lambda functions 
* HTTP APIs support OpenID Connect and OAuth 2.0 authorization. They come with built-in support for cross-origin resource sharing (CORS)  and automatic deployments.
* HTTP APIs use API Gateway Version 2 APIs, which previously supported only WebSocket APIs.



## Stage 
When a stage is defined on HTTP API, it creates a new path to the backend integration. 

| Stage    |      Path     |  
|----------|:--------------|
| $default | www.mydomain.com | 
| dev |    www.mydomain.com/dev  |   
|beta | www.mydomain.com/beta |  


## security
The APIs created with Amazon API Gateway expose HTTPS endpoints only. API Gateway doesn't support unencrypted (HTTP) endpoints. 
 HTTP APIs support only TLS 1.2.

[How Amazon API Gateway works with IAM](https://docs.aws.amazon.com/apigateway/latest/developerguide/security_iam_service-with-iam.html)
