 # CREATE S3 BUCKET AND EC2 INSTANCES FOR LINUX AND WINDOWS

## AIM :
To create an S3 bucket and EC2 instances for both Linux and Windows operating systems on AWS.

## PROBLEM STATEMENT :
This experiment demonstrates the process of setting up cloud infrastructure on AWS by creating an S3 bucket for storage and EC2 instances to host Linux and Windows environments. The goal is to provide an overview of how to configure and interact with these resources effectively, along with commands and screenshots to document the process.

## ALGORITHM :

#### Step 1:
Log in to AWS Console</br>

#### Step 2: Create an S3 Bucket</br>
Navigate to the S3 service.</br>
Click on Create bucket.</br>
Enter a Bucket name and select a Region.</br>
Configure Bucket settings as required (e.g., versioning, public access).</br>
Click on Create bucket to finalize.</br>

#### Step 3: Create an EC2 Instance (Linux)
Go to the EC2 service.</br>
Click on Launch Instance.</br>
Select an Amazon Machine Image (AMI) for Linux (e.g., Amazon Linux 2).</br>
Choose an Instance Type (e.g., t2.micro for free tier).</br>
Configure Instance Details, Storage, and Security Group.</br>
Review and click Launch with a key pair (or create one if needed).</br>

#### Step 4: Create an EC2 Instance (Windows)
Return to the EC2 service and click Launch Instance.</br>
Select a Windows AMI (e.g., Windows Server 2019).</br>
Choose the Instance Type.</br>
Configure Instance Details, Storage, and Security Group.</br>
Review and launch with a key pair (for future login).</br>

#### Step 5: Verify and Connect to Instances
Verify the status of both instances in the EC2 dashboard.</br>
Connect to the Linux instance using SSH.</br>
Connect to the Windows instance using RDP.</br>

### REG NUMBER : VARSHINI S A
### NAME : 212222100059

## OUTPUT
## S3 BUCKET CREATION:
![image](https://github.com/user-attachments/assets/1451504b-26b2-43a8-a733-cb476c7ee4ce)

### CONTENT IN BUCKET :
![Screenshot 2024-11-21 003651](https://github.com/user-attachments/assets/362b5b64-b4bb-491f-afcf-9e947226810b)

![image](https://github.com/user-attachments/assets/2a0f5d52-5e8b-4233-b86e-5451551273ce)

### VERSIONING :
![image](https://github.com/user-attachments/assets/140d8ce2-a630-43fa-8572-3b57d963b04f)

### REPLICATION :
![image](https://github.com/user-attachments/assets/916faa13-76b6-407a-831e-d8b92e509923)
![image](https://github.com/user-attachments/assets/b2f67958-840d-4657-8445-23c859ce5f18)

## EC2:
![Screenshot 2024-08-30 135806](https://github.com/user-attachments/assets/702d741c-3d06-430f-a420-95533cd8696c)

### Linux :
![Screenshot 2024-08-30 135908](https://github.com/user-attachments/assets/3af97a97-1d1e-4c15-92ff-191c7931e3cd)

![Screenshot 2024-08-30 135851](https://github.com/user-attachments/assets/f767b366-1df2-40d8-9e7d-f4694a26c09e)


### Windows :
![Screenshot 2024-08-30 134252](https://github.com/user-attachments/assets/bdf28d6c-5320-4271-88f2-448188f5cf0c)

## RESULT
 Successfully created an S3 bucket and EC2 instances for both Linux and Windows, demonstrating cloud resource management on AWS.


  


