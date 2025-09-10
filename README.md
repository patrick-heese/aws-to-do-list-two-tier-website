# aws-to-do-list-two-tier-website
A two-tier web application on AWS that hosts a Node.js To-Do List website on EC2 instances in public subnets with an Application Load Balancer, backed by a Multi-AZ RDS MySQL database in private subnets. All infrastructure is provisioned using nested CloudFormation stacks with a Bastion Host for one-time database initialization.
