 # CREATE S3 BUCKET AND EC2 INSTANCES FOR LINUX AND WINDOWS
### REG NUMBER : 212223110061
### NAME : S.VENGADA KRISHNAN
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



# OUTPUT

## S3 Bucket

![image](https://github.com/user-attachments/assets/ab22adaa-b90c-4b9b-9d58-f32550a1d244)

![image](https://github.com/user-attachments/assets/b0a87fdc-6506-4b81-96f0-2a24564cee81)



### VERSIONING :
![image](https://github.com/user-attachments/assets/dfa9b7e1-aac8-4215-ade1-bd50e5dcf0f1)

### REPLICATION :
![image](https://github.com/user-attachments/assets/87045f2f-0da6-4abe-9ec3-6da670530a43)
![image](https://github.com/user-attachments/assets/2c37a75d-18f0-4f0e-9324-4235ec14c0ef)



## EC2 Instance (LINUX)
![image](https://github.com/user-attachments/assets/e746a824-8f66-4193-be57-e83e6b050a81)

![image](https://github.com/user-attachments/assets/60c08db4-e0e2-4fa1-afcd-7b33bf52c6d5)



## EC2 INSTANCE (WINDOWS)

![image](https://github.com/user-attachments/assets/60587143-1cca-4cd6-adda-ed5e316ac261)




## RESULT
 Successfully created an S3 bucket and EC2 instances for both Linux and Windows, demonstrating cloud resource management on AWS.


  
