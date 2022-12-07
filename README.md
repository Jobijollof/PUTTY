# PUTTY
Connect to AWS ec2 instance using Putty

- Select region (launch a new EC2 instance of t2.micro family with Ubuntu Server 20.04 LTS (HVM)

- Create a key pair while creating your Ec2 instance. Click on `.ppk` to download a .ppk key as private key format.

![.ppk-format](./images/privatekey-format.png)

-Network settings allow  

- HTTP
   &
- HTTPS

![network-settings](./images/network%20settings.png)

- Leave every other configuration as default and Launch instance.

[Download putty here](https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html) Putty.exe

After download Run Putty, copy your public ipv4 address and paste

![host name for Ip address](./images/hostname4-ip.png ) as seen in the image

Click on `connection`: Input 30

Expand `SSH`, click on `AUTH` and browse for your ***.ppk***  private key.

![browse for key](./images/browse%20for%20key.png)

Click on Accept
![Accept](./images/acceptnew.png)

Login as Ubuntu

![login as ubuntu](./images/login.png)