# Day 1 – Create SSH Key Pair for Azure Virtual Machine 

## Objective
Create an SSH key pair in Azure to securely connect to a Virtual Machine.

## Services Used
- Azure Virtual Machines
- Azure Portal

## Steps Performed
- Logged in to the **Azure Portal**
- Navigated to **Virtual Machines**
- Started creating a new Virtual Machine
- In the **Administrator account** section:
   - Selected **SSH public key** as authentication type
   - Choose **Generate new key pair**
<img width="940" height="447" alt="image" src="https://github.com/user-attachments/assets/4300ac31-1ce7-4fc0-83b7-fb7659bdb9e1" />
<img width="940" height="616" alt="image" src="https://github.com/user-attachments/assets/331beba4-7ca5-44da-b429-e1dac6b97dd3" />

- Provided a name for the SSH key pair

<img width="940" height="874" alt="image" src="https://github.com/user-attachments/assets/4dbd4b9c-877a-4de4-8623-d7a4a6a57531" />

- Downloaded the private key (`.pem` file)

<img width="940" height="511" alt="image" src="https://github.com/user-attachments/assets/9f375135-0e89-47a9-ac95-b0a987996f41" />


## Outcome
- Successfully generated an SSH key pair
- Key pair is ready to be used for secure SSH access to Azure Virtual Machines

## Notes
- The private key file must be stored securely
- If the private key is lost, VM access cannot be recovered
- Azure automatically stores the public key

