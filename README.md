# CloudFormation
Automate webapp with multi AZ Load Balancer and VPC creation using CloudFormation

✔Step1:
Delete Default VPC

✔Step2: VPC CloudFormation Template
The template will create two subnets in different Availability Zones and add any necessary configuration to the CloudFormation Template.

The VPC will be configured with the following CIDR block: 10.0.0.0/16.

There will be two subnets in different AZs configured with the following CIDR blocks: 10.0.0.0/24 and 10.0.1.0/24.

Interchangeable EC2 instances will be spread across these Availability Zones, and therefore the subnets should have the same routing and security configurations.


✔Step3: WebApp CloudFormation Template
The WebApp CloudFormation Template is used to create an auto scaling, load balanced group of web servers that run on EC2. Attempt to execute the WebApp CloudFormation Template provided and resolve any errors until it successfully completes.




