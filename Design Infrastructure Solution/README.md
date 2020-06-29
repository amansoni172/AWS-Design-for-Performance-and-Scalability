## Design Infrastructure Solution

### Diagram 1
The infrastructure includes:

- Servers in the following region: us-east-1
- One VPC
- An S3 Bucket
- A NAT gateway
- Two Availability Zones
- AWS Route 53 Service
- Five Red Hat Enterprise web/application tier Linux m5.4xlarge instances in each *Availability Zone
- An AWS RDS database in the US with a read replica
- One Elastic Load Balancer with an Elastic IP address
- A DynamoDB database
- An AWS CloudFront Distribution
- All services in the diagram include a label to indicate the type of service and any necessary parameters (e.g. size, location)

Visible lines represent all network connections

### Diagram 2
The infrastructure includes:

- A user and client machine
- AWS Route 53
- A Cloudfront Distribution
- AWS Cognito
- AWS Lambda
- API Gateway
- DynamoDB
- S3 Storage
- All services in the diagram include a label to indicate the type of service and any necessary parameters (e.g. size, location)

Visible lines represent all network connections
