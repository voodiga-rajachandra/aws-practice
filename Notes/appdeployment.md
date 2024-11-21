# Deploy Application on Ec2 Using Httpd as Web-Server

***

**HTTPd stands for Hypertext Transfer Protocol daemon. 
It usually is the main software part of an HTTP server better known as a web serverSome commonly used implementations are: Apache HTTP Server**

## LAB

### Step1: Create EC2 Instance

***

**open aws console and search for EC2 service and once the page displayed click on launch instance as shown below**

![](images/appdep1.png)

**once the launch an instance page is displayed give a name for ec2 and also select ami as shown below**

![](images/appdep2.png)

**select instance type as t2.micro and click on create new keypair button as shown below**

![](images/appdep3.png)

**After clicking on create new keypair select the options as shown below and click on create keypair button**

![](images/appdep4.png)

**After creating keypair go to network settings and click on edit button**

![](images/appdep5.png)

**click on add security group rule and select http as shown below**
![](images/appdep6.png)

![](images/appdep7.png)

**click on launch instance as shown below**

![](images/appdep8.png)

**click on the instanceid as shown below**

![](images/appdep9.png)

**select the checkbox of our ec2 instance and click on connect button**

![](images/appdep10.png)

**selectssh client and copy the sshcode as shown below**

![](images/appdep11.png)

**open terminal and give command like cd Downloads where you downloaded the keypair, once the directory changed to the downloads paste the ssh key and press enter then it will connect to the instance**

![](images/appdep12.png)

**Enter the commands as shown below in the terminal**

![](images/appdep13.png)

![](images/appdep14.png)

![](images/appdep15.png)

![](images/appdep16.png)

**once the above commands executed go to console and click on the instance we created and copy the public ip address and paste it in the browser to check if the website is deployed or not**

![](images/appdep17.png)

**our website is deployed**
![](images/appdep18.png)
