# linuxactivity
---------------
- Steps for installing mysql on ubuntu 20.04 - [refer here] (https://linuxize.com/post/how-to-install-mysql-on-ubuntu-20-04/)
 
 - Initially, logging onto the existing ec2 machine:
![image](https://user-images.githubusercontent.com/103210706/162410038-3f645c92-3765-4d21-b19f-e8db6b8e7c2c.png)

- #Installing MySQL on Ubuntu 

- For updating packages from the internet, we run **sudo apt update** first
-  ![image](https://user-images.githubusercontent.com/103210706/162411410-3d00ba6b-78d4-4df9-8c25-bef9e2c4ece7.png)

- Then for installation of mysql, run **sudo apt install mysql-server**...

- Once the installation is completed, mysql is installed and running.

-   To verify if the mysql server is running, **sudo systemctl status mysql**

- ![image](https://user-images.githubusercontent.com/103210706/162413771-6414d626-064d-45b7-a5b2-56790666c14b.png)


- #Securing MySQL

![image](https://user-images.githubusercontent.com/103210706/162414169-ce06da7b-73b8-4cf4-a6a2-419ad769b0db.png)

-![image](https://user-images.githubusercontent.com/103210706/162414550-66cd7d36-3b6c-49bb-ab17-33492d5a0368.png)

![image](https://user-images.githubusercontent.com/103210706/162414731-e1cde94a-2af5-4419-af0f-61ac8a2401c8.png)


- To login as a root user on mysql

- Run **sudo mysql**
- ![image](https://user-images.githubusercontent.com/103210706/162415232-2082a7ed-e537-4984-9016-00148f9d2f88.png)
