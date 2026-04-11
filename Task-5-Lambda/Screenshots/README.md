# ⚡ Task 5: Serverless Function using AWS Lambda

## 📌 Objective

To deploy and execute code using AWS Lambda without managing servers.

---

## 🛠️ Steps Performed

* Created AWS Lambda function using Python runtime
* Wrote and deployed serverless code
* Configured API Gateway trigger
* Tested function using HTTP endpoint

---

## 💻 Code

```python
def lambda_handler(event, context):
    return {
        'statusCode': 200,
        'body': 'Hello from AWS Lambda 🚀'
    }
```

---

## 🌐 Output

Accessed Lambda function via API Gateway endpoint.

---



## 🚀 Key Learnings

* Serverless architecture 
* Event-driven execution
* No server management required
