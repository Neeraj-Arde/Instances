# Instances
Instance Deployment

Login to AWS account
Search for EC2 and select
Navigate to create a new Instance

Basics
Name: Can modify after deployment
OS Images: We can select from quick start AMI provided by AWS or can select if we have our own.
Instance Type: Select according to our workload M family for memory consumptioning, C for compute optimize, t family for general purpose and etc.
Key Pair: Select Key pair for Instance which will work as administrator password or if we dont have any key pair with us we can create a new.

Network setting (Will Cover networking part in other session in deep)
VPC: Choose VPC with required configuration (Can not be changed after deplyment)
Subnet: Define Subnet
Auto Assign Public IP: If we enable public IP from here it may get changed after a restart. (solution is elastic IP- will cover in specific part)
Security Group: Select appropriate SG for the instance or we can create a new one.
Private Ip can be selected while deployment if it is withing subnet range for that go to advanced settings and give required IP in Primary IP section.

Storage Configuration:
Add storage as per your requirement and storage type accordingly. (gp2/gp3/io1/io2 - each type has diffrent costing)

Advanced Details:
We can implement the changes after in this section.

Review the summary on left hand side and launch the instance.
