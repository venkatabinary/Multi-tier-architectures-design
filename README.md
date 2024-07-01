# Multi-tier-architectures-design
Multi-Tier Webarchitecture with serverless services

Based on https://docs.aws.amazon.com/whitepapers/latest/serverless-multi-tier-architectures-api-gateway-lambda/web-application.html
![image](https://github.com/venkatabinary/Multi-tier-architectures-design/assets/96198186/b69f54f6-5fcf-46ee-b986-a889282ce781)

Presentation <br>
Static content is hosted with Cloud Front <br>
Logic <br>
Logic of the Application is implemented with Lambda servces. Other options - ECS, EKS etc <br>
Data <br>
Data can be hosted based on the data types. It is implemented with Dynamo Db for NoSQL data types.
Other options based on data tupe - - RDS/OLTP, Redshift/OLAP, S3/static content. 
