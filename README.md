# EC2 Instance Creation

## **Aim**
To set up and launch an Amazon EC2 instance, providing on-demand computing services with flexible configurations for application deployment.


**Name**: Yuvaraj B
**Reg No**: 212222040186


## **Objectives**
1. **Log into AWS**: Access the AWS Management Console to create and manage resources.
2. **Launch EC2 Instance**: Configure the required instance parameters, including OS, storage, instance type, and network settings.
3. **Create Key Pair**: Generate a secure SSH key pair for EC2 access.
4. **Configure Network**: Adjust the instance’s VPC, subnets, and security groups as needed.
5. **Connect to Instance**: Use SSH to establish a connection to the EC2 instance.
6. **Automate EC2 Instance Creation**: Set up an Ansible playbook to automate the instance setup.
7. **Monitor Instance State**: Track instance states (running, stopped, terminated) and utilize AWS CloudWatch for performance monitoring.

---

## **Instructions**

### Step 1: Log into AWS Account
   - Open the AWS console and select **EC2** under **Services**.

![vcc1](https://github.com/user-attachments/assets/44fa39e0-9b38-4e17-9c7a-c20a1a99170e)


### Step 2: Launch an Instance
   - Click on **Launch Instance** and configure **AMI** (Amazon Machine Image) and **Instance Type** (e.g., `t2.micro` for free tier).

![vcc2](https://github.com/user-attachments/assets/613ba8f0-872e-4d7d-95bd-c93c56afd5fe)


### Step 3: Create Key Pair
   - Generate a **key pair** in `.pem` format, which will be downloaded for SSH access.

![vcc3](https://github.com/user-attachments/assets/c0910ce1-5909-4a53-8be9-3498eee43d02)


### Step 4: Configure Network and Storage
   - Keep **network settings** default, or customize for VPC, subnets, and security groups.
   - Choose the **EBS storage** (up to 30 GB free for eligible free-tier accounts).

![vcc4](https://github.com/user-attachments/assets/c0656c11-7fa4-4714-9004-17f64b7cf360)


### Step 5: Launch and Connect
   - Confirm configurations and click **Launch Instance**.
   - Connect to the instance using SSH from your terminal with the downloaded key pair.

![vcc5](https://github.com/user-attachments/assets/f59100ed-1281-46c2-a8ea-ee1927d5c0e5)


## **Results**

Successfully created the Elastic Compute Cloud (EC2) instances in this lab.
