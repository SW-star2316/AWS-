# AWS & EC2 Virtual Machine Written Description 
* Log in to your AWS Management Console.
Begin by accessing the AWS portal using your credentials.
* Launch a New Instance.
Navigate to the EC2 Dashboard and select "Launch an Instance."
* Name Your Instance.
Assign a recognizable name to your instance (e.g., “Windows”).
* Select an Amazon Machine Image (AMI).
Choose Microsoft Windows as your operating system.
* Choose an Instance Type.
Select t2.xlarge as the instance type to allocate sufficient resources.
* Create a Key Pair.
Generate a new key pair, or use an existing one, to securely access the instance. Be sure to download and store the .pem file securely.
* Launch the Instance.
Review your configuration and click "Launch Instance" to initiate deployment.
* Configure Security Group Settings.
Once the instance is launching, modify the Security Group to allow RDP (Remote Desktop Protocol) by opening port 3389.
* Wait for the Instance to Initialize.
Monitor the instance status until it shows as “Running” and “Status Checks: 2/2 passed.”
* Retrieve the Administrator Password.
Once the instance is ready, select the instance and click "Get Windows Password". You will use your previously created key pair to decrypt the password.
* Connect via Remote Desktop (RDP).
Use the decrypted password along with the public IPv4 address of the instance to connect through Remote Desktop Connection on your local machine.



# EC2 Windows 
https://www.loom.com/share/2498340303ab4606be89517189a4093a?sid=407caa75-9c86-4a9b-b8da-0121b86028f5
# Lab 
This lab was about setting up a virtual computer in the cloud to practice using Windows tools. We used Amazon Web Services (AWS), mainly the EC2 service, to do this. You needed an AWS account to get started and use the different cloud features. 
# EC2 step by step 
![image](https://github.com/user-attachments/assets/8fd67e21-e86b-4a12-bda9-38d80651d814)
![image](https://github.com/user-attachments/assets/abc4a438-561e-452a-bf05-c6663a20597c)
![image](https://github.com/user-attachments/assets/b6c49da0-0027-4b77-84ee-59e4ce2279f4)
![image](https://github.com/user-attachments/assets/d7fd3534-af04-4699-86b4-8f041fb6aec3)
