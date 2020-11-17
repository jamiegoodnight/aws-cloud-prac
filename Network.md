Region - geographical location
AZ - data center for aws resources
vpc - logically isolated section of the aws cloud you can launch aws resources
subnet - a logical partition of an IP network into multiple, smaller networks segments (public and private subnets/accessible to Internet and not)
Internet Gateway - Door to the internet/Enable access 
Route Table - Determine where network traffic from your subnets are directed (go to the Internet)
Security Group - Acts as a firewall at the instance level. 
NACLs - Firewall at subnet level 


______________________________

DATABASE services

DynamoDB* - NoSQL key/value database
Aurora Serverless* - Less features, way more inexpensive. 
Redshift* -Columnar database. Reads via columns. Works with huge amounts of data. 
Aurora - for MySQL and PostGreSQL "Full managed" with better performance. More expensive. 
RDS* - Most commonly used. Relational database service. Uses MySQL, etc.

Neptune - Managed graph database. 
ElastiCache - Caching solution. 
DocumentDB - NoSQL Document database that is MongoDB compatible

_________________________________

Provisioning 

The allocation and creation of resources to a customer. 

Elastic Beanstalk - Service for deploying web application. Prepare codes. Choose container. Heroku for AWS. 

Opsworks - Confirguration management service that provides managed instances of chef and puppet. 

CloudsFormation - Infrastructure as code. JSON or YAML.

AWS QuickStart - pre-made packages that can launch and configure your AWS compute, networks, storage, required to deploy a workload on AWS. 

AWS Marketplace - a digital catalogue of software compatible with AWS. 