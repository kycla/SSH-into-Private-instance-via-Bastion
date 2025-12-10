# SSH into Private instance via Bastion

## Objective

This lab will showcase how to create a VPC from scratch in AWS along with its subnets and gateways. Then you will see how you can connect to the instnaces in both the public and private subnet.

### Skills Learned
[Bullet Points - Remove this afterwards]

- Advanced understanding of SIEM concepts and practical application.
- Proficiency in analyzing and interpreting network logs.
- Ability to generate and recognize attack signatures and patterns.
- Enhanced knowledge of network protocols and security vulnerabilities.
- Development of critical thinking and problem-solving skills in cybersecurity.

### Tools Used
[Bullet Points - Remove this afterwards]

- Security Information and Event Management (SIEM) system for log ingestion and analysis.
- Network analysis tools (such as Wireshark) for capturing and examining network traffic.
- Telemetry generation tools to create realistic network traffic and attack scenarios.

# Steps 

## VPC Creation

### Step 1
- I will navigate to the VPC console, click create a VPC, and name the VPC "Lab VPC".
- I have set the CIDR as 10.0.0.0/16 so my VPC will have enough room for subnets /24
<img width="1513" height="1090" alt="Screenshot 2025-12-09 202121" src="https://github.com/user-attachments/assets/6227af27-33bc-4835-83c2-640d8e040e16" />


*Ref 1: VPC creation*

## Creating Subnets

### Step 1 
- Now I will create 4 subnets, 2 for each Availability Zomain.
- I will start with my public subnets
<img width="1205" height="1009" alt="Screenshot 2025-12-09 210212" src="https://github.com/user-attachments/assets/9699ee60-f8cc-4b3f-91e9-cdb9d09d5835" />

*Ref 2: Public Subnet creation*
- As you can see I have placed each public subnet in a different Availability Zone

### Step 2
- On to the next step, I will do the same as the previous process but make it private.
- 










