
# AWS Application Load Balancer – Best Practice Architecture

This project demonstrates how to design and deploy a secure and highly available web architecture using AWS Application Load Balancer (ALB). The infrastructure is built following cloud best practices to ensure scalability, security, and efficient traffic distribution.

The architecture includes a custom VPC with multiple subnets across different availability zones, where the Application Load Balancer is placed in public subnets and EC2 instances are deployed in private subnets. The ALB distributes incoming traffic across multiple instances using target groups and health checks to maintain reliability and availability.

This project showcases important AWS networking and load balancing concepts such as VPC configuration, subnet design, security groups, target group management, and load balancing strategies, making it a practical example of how modern cloud-based web applications are deployed.
