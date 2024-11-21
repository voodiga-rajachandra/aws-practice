# Project Overview: Real-Time Web Application in AWS VPC
***

**We will create a web application that can receive requests over the internet and respond in real-time. This will include:**

1. **Creating a VPC**
2. **Creating subnets**
3. **Setting up an Internet Gateway**
4. **Configuring route tables**
5. **Setting up Network ACLs**
6. **Launching an EC2 instance to serve the web application**

**Step 1: Create a VPC**
***
**Log in to the AWS Management Console and navigate to the VPC dashboard and click on create vpc button**

![](images/vpc1.png)

**After clicking on create vpc button you will be redirected to create vpc page in this page give the vpc a name also give the cidr range and click on create vpc button**

![](images/vpc2.png)

![](images/vpc3.png)

**after completing the above process vpc will be created**

![](images/vpc4.png)

**Step 2: Create Subnets**
***
**In the vpc dashboard click on subnets and click on create subnet button**

![](images/vpc5.png)

**u will be redirected to create subnets page where u need to create two subnets one is public subnet and other one is private subnet**

![](images/vpc6.png)

![](images/vpc7.png)

![](images/vpc8.png)

![](images/vpc9.png)

**private subnet and public subnet will be created as shown below**

![](images/vpc12.png)

### Step 3: Set Up an Internet Gateway
***
**click on internet gateway in vpc dashboard and click on internet gateway button**

![](images/vpc13.png)

**once u click on internet gateway button u will be redirected to create internet gateway page there give the internet gateway name and click on create internet gateway button**

![](images/vpc14.png)

**click on attach to vpc button to attach internet gateway to vpc**

![](images/vpc15.png)

**select the vpc that we created and click on attach internet gateway button**

![](images/vpc16.png)

![](images/vpc17.png)

### Step 4: Configure Route Tables
***
**Create a Route Table for the Public Subnet:**
![](images/vpc18.png)

![](images/vpc19.png)

![](images/vpc20.png)

![](images/vpc21.png)

![](images/vpc22.png)

![](images/vpc23.png)

![](images/vpc24.png)

### Step 5: Set Up Network ACLs

***

![](images/vpc26.png)

![](images/vpc27.png)

![](images/vpc28.png)

![](images/vpc29.png)

![](images/vpc30.png)

![](images/vpc31.png)

![](images/vpc32.png)

![](images/task1error.png)

### Step 6: Launch an EC2 Instance

***
![](images/vpc35.png)

![](images/vpc36.png)

![](images/vpcoutput.png)