# PUTTY
Connect to AWS ec2 instance using Putty

- Select region (launch a new EC2 instance of t2.micro family with Ubuntu Server 20.04 LTS (HVM)

- Create a key pair while creating your Ec2 instance. Create a key pair and choose download  .ppk as private key format.

![.ppm-format](./images/privatekey-format.png)

-Network settings allow  

- HTTP
   &
- HTTPS

![network-settings](./images/network%20settings.png)

- Leave everyother configuration as default and Launch instance.

[Download putty here](https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html) Putty.exe

After download Run Putty, copy your public ipv4 address and paste

![host name for Ip address](./images/hostname4-ip.png ) as seen in the image

Click on connection, input 30

Expand SSH, click on AUTH and browse for your key.

![browse for key](./images/browse%20for%20key.png)

Click on Accept
![Accept](./images/accept.png)

Login as Ubuntu

![login as ubuntu](./images/login.png)