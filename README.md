# cloud_exploration

An exploration into standing up a full server on AWS with Pulumi.

## Requirements

- **Route 53**  
- **S3** – 2 buckets  
- **CloudFront** – 2 distributions  
- **ECS Fargate** – service with 2 tasks  
- **Application Load Balancer**  
- **Amazon RDS** – Multi-AZ `db.t3.micro` instance  
- **AWS Secrets Manager**  
- **VPC** – single VPC with public/private subnets  
- **CloudWatch** – logs and alarms  
