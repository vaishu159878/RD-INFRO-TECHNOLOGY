#  Task 3: Auto Scaling and Load Balancer Setup

##  Objective

To create a scalable cloud environment where EC2 instances automatically scale based on traffic.

---

##  Steps Performed

* Created Launch Template with web server setup using user data
* Configured Target Group for instance health checks
* Set up Application Load Balancer to distribute traffic
* Created Auto Scaling Group with min, desired, and max instances
* Configured scaling policies based on CPU utilization

---

##  Output

Accessed application using Load Balancer DNS and observed traffic distribution across multiple instances.

---

##  User Data Script

```
#!/bin/bash
sudo yum update -y
sudo yum install httpd -y
echo "This is my webserver $HOSTNAME" > /var/www/html/index.html
sudo systemctl start httpd
sudo systemctl enable httpd
```

---


##  Key Learnings

* Load balancing and traffic distribution
* Auto Scaling for high availability
* Real-world cloud architecture basics
