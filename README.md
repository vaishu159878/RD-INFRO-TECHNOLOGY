# 🚀 Task 1: Launch Virtual Machine (EC2)

## 📌 Objective
To create and configure a virtual machine on AWS and host a web server.

---

## Steps Performed
- Launched EC2 instance using Ubuntu
- Configured security groups (SSH & HTTP)
- Connected to instance using SSH
- Installed Apache Web Server
- Verified deployment using browser

---

## Commands Used

chmod 400 my-key.pem
ssh -i "my-key.pem" ubuntu@13.63.157.110
sudo apt update
sudo apt install apache2 -y
sudo systemctl start apache2
