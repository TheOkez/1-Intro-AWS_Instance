# Introduction to Amazon Elastic Compute Cloud (EC2)

## 📌 Project Overview
This project demonstrates how to launch and configure a virtual machine in the Amazon Web Services (AWS) cloud using **Amazon Elastic Compute Cloud (EC2)**.

The lab covers the complete lifecycle of an EC2 instance — from selecting an Amazon Machine Image (AMI) to deploying a publicly accessible web page using Apache HTTP Server.

---

## 🎯 Objectives
By completing this project, I was able to:

- Launch and configure an EC2 instance in AWS  
- Select and use an Amazon Machine Image (AMI)  
- Configure security groups for SSH and HTTP access  
- Connect to an EC2 instance using SSH  
- Install and manage Apache HTTP Server  
- Deploy and access a public web page  

---

## 🛠 AWS Services & Tools Used
- Amazon EC2  
- Amazon Linux 2023  
- Amazon Machine Images (AMI)  
- Security Groups  
- SSH (Key Pair authentication)  
- Apache HTTP Server  

---

## 🚀 Project Implementation

### 1️⃣ Selecting an Amazon Machine Image (AMI)
Amazon Linux was selected as the operating system for the EC2 instance.

![AMI Selection](Images/Capture%20d'écran%202025-12-14%20130207.png)
![AMI Options](Images/Capture%20d'écran%202025-12-14%20130254.png)

---

### 2️⃣ Configuring the Security Group
A security group was created to allow:
- SSH access on port 22  
- HTTP access on port 80  

![Security Group Name](Images/Capture%20d'écran%202025-12-14%20130315.png)
![Security Group Rules](Images/Capture%20d'écran%202025-12-14%20130354.png)

---

### 3️⃣ Launching the EC2 Instance
The EC2 instance was launched successfully and verified to be in a **running** state.

![Instance Running](Images/Capture%20d'écran%202025-12-14%20130459.png)

---

### 4️⃣ Viewing Instance Details
Key instance information such as instance ID, instance type, public IP address, and DNS name were reviewed.

![Instance Summary](Images/Capture%20d'écran%202025-12-14%20130724.png)

---

### 5️⃣ Connecting to the Instance via SSH
A secure SSH connection was established using the key pair.  
The host authenticity was confirmed during the initial connection.

![SSH Confirmation](Images/Screenshot%20Capture%20-%202025-12-14%20-%2012-43-35.png)
![SSH Login](Images/Screenshot%20Capture%20-%202025-12-14%20-%2012-49-47.png)

---

### 6️⃣ Updating the System
The instance was updated to ensure all packages were current.

![System Update](Images/Screenshot%20Capture%20-%202025-12-14%20-%2012-58-48.png)

---

### 7️⃣ Installing and Starting Apache HTTP Server
Apache was installed, started, enabled on boot, and verified as running.

![Apache Status](Images/Screenshot%20Capture%20-%202025-12-14%20-%2013-01-07.png)

---

### 8️⃣ Creating and Deploying the Web Page
A simple HTML page was created in the Apache web directory and the service was restarted.

![Web Page Creation](Images/Screenshot%20Capture%20-%202025-12-14%20-%2013-08-18.png)

---

### 9️⃣ Accessing the Public Web Page
The deployed web page was accessed using the EC2 instance’s public IP address.

![Live Web Page](Images/Screenshot%20Capture%20-%202025-12-14%20-%2013-08-18.png)

---

## ✅ Final Outcome
At the end of this project:
- An EC2 instance was successfully launched and configured  
- Secure SSH access was established  
- Apache HTTP Server was installed and running  
- A public web page was deployed and accessible  

---

## 📚 Key Learnings
- Understanding the EC2 launch process  
- Using security groups to control network access  
- Managing Linux services with `systemctl`  
- Hosting a basic web application on AWS  


