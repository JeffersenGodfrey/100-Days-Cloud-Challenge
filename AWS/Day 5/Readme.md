# Day 5 – Create a GP3 EBS Volume

## Objective
Create a GP3 (General Purpose SSD) EBS volume in AWS to provide scalable and high-performance storage for EC2 instances.

## Services Used
- Amazon EC2 (EBS Volumes)

## Steps Performed
- Logged in to the AWS Management Console via lab credentials
- Navigated to **EC2 Dashboard**
- Clicked on **Volumes** under **Elastic Block Store** in the left-hand menu
- Clicked **Create volume**


- Selected:
   - Volume type: **GP3**
   - Size (GiB): **Enter desired size (e.g., 20 GiB)**
   - Availability Zone: **Select the same AZ as your EC2 instance**
   - IOPS: **Default or custom as required**
   - Throughput: **Default or custom as required**
- Clicked **Create volume**
<img width="940" height="379" alt="image" src="https://github.com/user-attachments/assets/9483bb95-9fb6-4cee-b017-e21062d7e9e1" />


## Outcome
- Successfully created a GP3 EBS volume
- Volume is ready to attach to an EC2 instance for high-performance storage
<img width="940" height="467" alt="image" src="https://github.com/user-attachments/assets/840950a3-1fd0-41f1-b918-6a0811e20ec4" />
<img width="940" height="623" alt="image" src="https://github.com/user-attachments/assets/3e87655f-1194-4a40-bb62-c5f613721fd5" />

## Notes
- GP3 volumes provide higher baseline performance than GP2 with configurable IOPS and throughput
- Always ensure the volume is in the same Availability Zone as the EC2 instance before attaching
- GP3 is cost-effective and ideal for general-purpose workloads
