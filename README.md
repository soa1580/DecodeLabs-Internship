# In this project, I would be showing how I make a Linux virtual machine provision, connect using SSH, install a web server, and host a custom website displaying "Welcome to DecodeLabs"


## Step 1: Provisioning a Linux Virtual Machine, I used Amazon Web Services (AWS) Elastic Compute Cloud (EC2)EC2 service.

![EC2 Instance Running](./img/EC2-instance-running.png)


## Step 2: I created a security group rule to allow inbound traffic on port 80 (HTTP) and port 22 (SSH) to access the web server and connect to the instance securely.

![Security Group Rule](./img/security-group-rules.png)


## Step 3: I connected to the EC2 instance using SSH (Secure Shell) from my local machine.

![SSH Terminal Connected](./img/ssh-terminal-connected1.png)


## Step 4: I installed a web server (Apache) on the EC2 instance to serve web pages.

![Apache Installed](./img/apache-installed.png)


## Step 5: Finally, I accessed my custom website by entering the public IP address of the EC2 instance in a web browser, and it displayed "Welcome to DecodeLabs".

![Website Running in Browser](./img/website-running-in-browser.png)






