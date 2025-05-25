##Terraform Static Website Deployment on AWS EC2
This project uses **Terraform** to deploy a static "Hello World" website on AWS. The infrastructure includes:
- A custom VPC with public subnets
- An Application Load Balancer (ALB)
- An Auto Scaling Group (ASG) for EC2 instances
- A Launch Template to define EC2 settings and user data
- A Security Group that allows HTTP traffic

##Prerequisites
Make sure the followings are installed:
- Terraform(https://developer.hashicorp.com/terraform/downloads)
- AWS CLI(https://aws.amazon.com/cli/)
- An AWS account with an IAM user configured via `aws configure`

##To use
terraform init
terraform plan
terraform apply
(type "yes" to confirm)

##What to expect
The following static website should be seen:
"Hello World from <EC2 instance hostname>"

##To clean up
terraform destroy

