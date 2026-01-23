# Day 6 – Launch an EC2 Instance

## Objective
Launch an Amazon EC2 instance to provision a virtual server in the AWS cloud for compute workloads.

## Services Used
- Amazon EC2

## Steps Performed
- Logged in to the AWS Management Console via lab credentials
- Navigated to **EC2 Dashboard**
- Clicked **Launch instance**
<img width="940" height="646" alt="image" src="https://github.com/user-attachments/assets/f66d49c4-f37e-4a6c-8519-8ab5c2373aa5" />

- Entered an **EC2 instance name**
- Selected an **Amazon Machine Image (AMI)** (e.g., Amazon Linux)
- Chose instance type: **t2.micro  (Free Tier eligible)**
- Create a key pair **Key pair** 
<img width="940" height="921" alt="image" src="https://github.com/user-attachments/assets/2755bfbd-e209-41da-88b7-2e3223fa61ac" />

- Configured **Network settings**:
  - Selected VPC
  - Selected Subnet
- Choose default **Security Group**:
<img width="940" height="568" alt="image" src="https://github.com/user-attachments/assets/8a2a3235-74c9-45ec-a863-401945822259" />

- Reviewed configuration and clicked **Launch instance**
<img width="940" height="466" alt="image" src="https://github.com/user-attachments/assets/41d637d3-7085-45b2-b702-3f9c35920384" />


## Outcome
- EC2 instance launched successfully
- Instance is in running state and ready for access

## Notes
- Always use a secure key pair for SSH access
- Security groups act as a virtual firewall for EC2 instances
- Stop or terminate instances when not in use to avoid unnecessary costs
