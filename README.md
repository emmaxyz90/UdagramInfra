### Project Title - Deploy a high-availability web app using CloudFormation
This is a cloudformation template for the "ND9991 - C2- Infrastructure as Code which Deploys a high-availability web app using CloudFormation" project. This folder contains the following files:


#### projectTwo.yml
This is a script that deploys the networking infrastructure as seen in the architecture diagram for the IAAC. Components includes the VPC, public subnet & private subnets, Internet gateway, Route tables, NAT Gateway and Elastic IP address. 

#### server.yml
This is a script that deploys the server section of the infrasatructure, which includes the load balancer, ec2 instances(servers) using a launch configuration, autoscaling group that ensures high availability of the service, target groups and security groups on Port 80.

#### server-parameters.json
The parameters for creating the server infrastructure.


Load Balancer URL (Endpoint): 

Proje-WebAp-1JTAO9SQ97IS9-1718455537.us-east-1.elb.amazonaws.com
