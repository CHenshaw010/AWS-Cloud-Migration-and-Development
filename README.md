### Migrating and Developing a Full-Stack Application to the Cloud with AWS
- Docker Files
  - [lafs-web Docker](https://github.com/CHenshaw010/AWS-Cloud-Migration-and-Development/blob/main/lafs-web%20Dockerfile/Dockerfile)
  - [lafs-api Docker](https://github.com/CHenshaw010/AWS-Cloud-Migration-and-Development/blob/main/lafs-api%20Dockerfile/Dockerfile)
- Docker Compose Files
  - [lafs-web Docker Compose](https://github.com/CHenshaw010/AWS-Cloud-Migration-and-Development/blob/main/lafs-web%20docker-compose/docker-compose.yaml)
  - [lafs-api Docker Compose](https://github.com/CHenshaw010/AWS-Cloud-Migration-and-Development/blob/main/lafs-api%20docker-compose/docker-compose.yaml)
- Documentation/Personal Reflection
  - [Cloud Migration Reflection](https://github.com/CHenshaw010/AWS-Cloud-Migration-and-Development/blob/main/Documentation%20and%20Final%20Reflection.pdf)

## Summary
This application demonstrates the process of migrating a full-stack MongoDB, Express, Angular, and Node.js (MEAN) application to the cloud with Amazon Web Services (AWS). To do so, we utilized Simple Storage Service (S3) for the nearly limitless storage and retrieval of data, Lambda and Application Programming Interface (API) Gateway for highly configurable APIs, and DynamoDB for database operations. The API utilized many Hypertext Transfer Protocol (HTTP) methods such as GET, POST, PUT, and DELETE to perform the CRUD operations on the DynamoDB database and to connect the frontend interface with the backend logic. Furthermore, AWS Identity and Access Management (IAM) roles and policies were thoroughly utilized to define permissible actions and comprehensively secure applications.

## Cloud Migration and Development Presentation
[AWS Cloud Development](https://www.youtube.com/watch?v=5KJPgwHqYd0)

## Cloud Endpoint
[S3](http://chsnhuaws.s3-website-us-east-1.amazonaws.com)

## Important Note
Due to the nature of cloud services and the security features that create unique IDs, it would be both redundant and a security risk to post any of the AWS code to GitHub. This is why only the Docker files, Docker Compose files, and cloud development presentations are available.
