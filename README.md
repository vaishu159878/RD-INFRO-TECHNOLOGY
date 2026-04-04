#  Cloud Computing Internship - RD INFRO TECHNOLOGY

This repository contains tasks completed as part of my Cloud Computing Internship.

---

#  Task 1: Launch Virtual Machine (EC2)

##  Objective

To create and configure a virtual machine on AWS and host a web server.

##  Steps Performed

* Launched EC2 instance using Ubuntu
* Configured security groups (SSH & HTTP)
* Connected to instance using SSH
* Installed Apache Web Server
* Verified deployment in browser using public IP

##  Commands Used

```
chmod 400 my-key.pem
ssh -i "my-key.pem" ubuntu@13.63.157.110
sudo apt update
sudo apt install apache2 -y
sudo systemctl start apache2
```

---

#  Task 2: S3 Static Website Hosting

##  Objective

To host a static website using AWS S3.

## Steps Performed

* Created S3 bucket
* Enabled static website hosting
* Uploaded index.html file
* Configured bucket permissions for public access
* Accessed website using S3 endpoint URL

---

## Tools Used

* AWS EC2
* AWS S3
* Linux (Ubuntu)
* GitHub

---

## Author

Vaishnavi Nalawade
