# Make an ec2 in public subnet accessible over ssh

## Given
- public subnet is there i.e. igw is having route in route table connected to subnet for for 0.0.0.0/0

## Steps
Open Ec2 service in console and choose following
- region
- AMI
- instance type e.g. t3.micro etc.
- Key Pair
- Network i.e. VPC,subnet and sec group
- Volume
- in sec group create ingress for ssh on port 22

## Concepts
### aws
- public subnet is where igw is having route in route table connected to subnet for for 0.0.0.0/0