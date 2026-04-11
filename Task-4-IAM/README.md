# 🔐 Task 4: IAM Roles and Policies

## 📌 Objective

To manage access control in AWS by creating IAM users, roles, and policies.

---

## 🛠️ Steps Performed

* Created IAM user with console access
* Assigned permissions using AWS managed policies
* Created custom policy using JSON
* Created IAM role for EC2 service
* Attached policies to users and roles

---

## 💻 Sample Policy

```json
{
    "Version": "2012-10-17",
    "Statement": [
        {
            "Effect": "Allow",
            "Action": "s3:*",
            "Resource": "*"
        }
    ]
}
```

---



## 🚀 Key Learnings

* Identity and Access Management in AWS
* Role-based access control
* Importance of least privilege principle
* Securing cloud resources using IAM
