HTTP APIs is at least 71% lower cost compared to API Gateway REST APIs.

[https://aws.amazon.com/blogs/compute/building-better-apis-http-apis-now-generally-available/](https://aws.amazon.com/blogs/compute/building-better-apis-http-apis-now-generally-available/)


## Stage 
When a stage is defined on HTTP API, it creates a new path to the backend integration. 

| Stage    |      Path     |  
|----------|:--------------|
| $default | www.mydomain.com | 
| dev |    www.mydomain.com/dev  |   
|beta | www.mydomain.com/beta |  
