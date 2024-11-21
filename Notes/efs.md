# EFS

**From the aforementioned list, EFS falls under the file storage category. EFS is a file-level, fully managed, storage provided by AWS (Amazon Web Services) that can be accessed by multiple EC2 instances concurrently. Just like the AWS EBS, EFS is specially designed for high throughput and low latency applications**

**EFS can be created using the EC2-Instance where it will be created in a specific region and distributed across multiple availability zones for the purpose of high availability and durability. You can choose the EFS based on the I/Ops you are going to perform**

### LAB

### Step1: search for efs service on aws console and click on Create File system
***
![](images/efs1.png)

### Step2: give the name for efs and click on create button
***
![](images/efs2.png)

### Step3: efs will be created and u can see the efs id
![](images/efs3.png)
***
### Step4: search for ec2 service on aws console and click on launch instance
![](images/efs4.png)
***
### Step5: Launch an instance page will be displayed give the name ec2 instance
![](images/efs5.png)
***
### Step6: select ami,instance type and create keypair
![](images/efs6.png)

![](images/efs7.png)


### Step7: Add security group rule (ssh and http) and create launch instance button which will be right bottom

![](images/efs8.png)

![](images/efs9.png)

***
### Step8: ec2 st1 instance will be created

![](images/efs10.png)

***
### Step9: search for vpc in console on left side menu click on security group and also click on security group button on right side top
![](images/efs20.png)
***
### Step10: give the port 2049 in inbound rules
![](images/efs21.png)
***
### Step11: click on create security group button
![](images/efs22.png)
***
### Step12: Security group will be created
![](images/efs23.png)
***
### Step13: go to efs select network
![](images/efs24.png)
***
### Step14: click on manage button
![](images/efs25.png)
***
### Step15: select the security groups and choose the security group what we created in before steps and click on save
![](images/efs26.png)
![](images/efs27.png)
![](images/efs28.png)

### Step16: go to the ec2 instance we created and click on connect button and copy the ssh code
![](images/efs30.png)
![](images/efs31.png)
***
### Step17: go terminal and go to drive where u keypair is downloaded and paste the ssh code for connecting the instance
![](images/efs32.png)
***
### Step18: make a directory efs
![](images/efs32.png)
***
### Step19:go to efs which we created and click on attach a mount code will be displayed
![](images/efs33.png)
![](images/efs34.png)
***
### Step20: go to terminal where your ec2 instance created and make a directory efs and paste the mount code after that create a folder and file in efs folder
![](images/efs35.png)
***

### Step21: Create ec2 instance 2 and click on connect button copy the ssh code
![](images/efsst21.png)
![](images/efsst22.png)
![](images/efsst23.png)
***

### Step22: go to the terminal and copy the ssh code and create ec2 connection and make directory efs and paste the efs mount code and go efs directory and check the folders and files
![](images/efsst24.png)
***