# Day 1 – Create a Key Pair in AWS 

## Objective
Create an SSH key pair in AWS to securely connect to EC2 instances.

## Services Used
- Amazon EC2

## Steps Performed
<img width="940" height="497" alt="image" src="https://github.com/user-attachments/assets/f08ceea3-a79a-4683-a7fd-23870de9c9e1" />

- Logged in to the AWS Management Console via the lab credentials
- Navigated to **EC2 Dashboard**
- Choose **Key Pairs** from EC2 launch instance.
<img width="940" height="374" alt="image" src="https://github.com/user-attachments/assets/a4ff52e6-fe44-4091-95b5-b73772212c37" />
<img width="940" height="465" alt="image" src="https://github.com/user-attachments/assets/7e5f6e36-f8ec-4391-8da4-384e97b251b2" />
- Clicked **Create key pair**
- Entered key pair name
- Selected:
   - Key pair type: **RSA**
   - Private key format: **.pem**
- Downloaded and securely stored the key pair
<img width="940" height="519" alt="image" src="https://github.com/user-attachments/assets/7337ba14-8408-4d6a-91d5-133fb6fe08dd" />


## Outcome
- Successfully created an EC2 key pair
- Key pair is ready to be used for SSH access to EC2 instances

## Notes
- The `.pem` file should never be shared
- Lost key pairs cannot be recovered and must be recreated



