# Cloud-Storage-creation-S3-and-Launching-an-EC2-Instance-in-AWS
Ex.2 Cloud storage creation (S3) and launching an (Ec2) instance in AWS
Aim:
To create a Simple Storage Service (S3) in AWS and to launch an EC2 instance in AWS. 
Procedure
a)	Steps to Create a first S3 Bucket:
Step 1: Sign in to the AWS Management Console
Go to https://console.aws.amazon.com/s3.
Step 2: Open the S3 Service
In the console, type S3 in the search bar and select S3 to open the service dashboard.
Step 3: Create Bucket
Click the Create bucket button.
Step 4: Configure Bucket Settings
•	Bucket name: Choose a globally unique name.
•	AWS Region: Select the region where you want to store your data.
Step 5: Object Ownership
Choose between:
	ACLs disabled (recommended) – Bucket owner has full control.
	ACLs enabled – Control access via access control lists.
Step 6: Block Public Access Settings
By default, all public access is blocked. Leave it as-is unless you need public access.
Step 7: Bucket Versioning (optional)
Choose whether to enable versioning for objects in the bucket.
Step 8: Encryption (optional)
Select encryption options (SSE-S3, SSE-KMS, or none).
Step 9: Advanced Settings (optional)
Add tags, configure logging, etc.
Step 10: Create the Bucket
Click Create bucket at the bottom of the page.
b)	i. Steps to launch an EC2 Instance
1.	Go to the EC2 Dashboard in AWS Console.
2.	Click on “Launch Instance”.
3.	Choose an Amazon Machine Image (AMI) (e.g., Amazon Linux).
4.	Select an instance type (e.g., t2.micro for Free Tier).

5.	Create or choose a key pair for SSH access.
6.	Configure network settings (use default VPC/subnet).
7.	Configure storage (default root volume is fine).
8.	Review the settings and click “Launch Instance”.
9.	Wait for the instance to enter the running state.

c)	Step 3: Connect to Your Instance
•	Linux: Use SSH command with your .pem key.
•	Windows: Use RDP with decrypted admin password.

d)	Steps to Clean Up (Terminate the Instance)
1.	Go to EC2 Instances.
2.	Select your instance → Instance State → Terminate.


Snap Shots:
 <img width="960" height="564" alt="Screenshot 2026-11-01 182529" src="https://github.com/user-attachments/assets/20651e50-0c4b-4106-a6ac-f8d1e8cd28b4" />
<img width="960" height="564" alt="Screenshot 2026-11-02 151646" src="https://github.com/user-attachments/assets/44838d11-fdfe-4446-b330-0ac3c0bf9176" />
<img width="960" height="564" alt="Screenshot 2026-11-02 155445" src="https://github.com/user-attachments/assets/0cbd850c-b69e-49e3-988c-99ff7e4c608b" />
<img width="960" height="564" alt="Screenshot 2026-11-02 160634" src="https://github.com/user-attachments/assets/0e4608b0-57d1-4027-99b7-ab2d50bb26e1" />
<img width="960" height="564" alt="Screenshot 2026-11-02 155510" src="https://github.com/user-attachments/assets/39fb5d63-50b7-45d6-b4e8-ba410543e9a1" />
<img width="960" height="564" alt="Screenshot 2026-11-02 160711" src="https://github.com/user-attachments/assets/3155d26e-162d-4fad-931a-30a5e9661009" />
<img width="960" height="564" alt="Screenshot 2026-11-02 160839" src="https://github.com/user-attachments/assets/af8e5a31-6d1b-44f0-9647-b53e6102754e" />
<img width="960" height="564" alt="Screenshot 2026-11-02 161144" src="https://github.com/user-attachments/assets/1daffc25-f0ce-4563-b4a2-00f1feffad5a" />
<img width="960" height="564" alt="Screenshot 2026-11-02 161214" src="https://github.com/user-attachments/assets/8baa538d-d081-43b1-9238-a40033072a4e" />
<img width="960" height="564" alt="Screenshot 2026-11-02 143450" src="https://github.com/user-attachments/assets/f93c3edb-5e61-4599-a4e1-4096910bfcdf" />

Result:
Thus, a Simple Storage Service (S3) and EC2 (Elastic Compute Cloud) - instance has been successfully created and launched in AWS
 
