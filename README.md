# 🌐 Rise Internship AWS Projects

This repository contains two AWS-based static website hosting projects:

- ✅ **Project 1**: Host a website using EC2 + Nginx  
- ✅ **Project 2**: Host a website using S3 + CloudFront

---

## ✅ Project 1: EC2 + Nginx Static Website Hosting

A basic static website hosted using an Ubuntu EC2 instance and Nginx web server.

### 🛠️ Steps:
1. Launched a free-tier EC2 (Ubuntu) instance
2. Configured security group to allow HTTP & SSH
3. SSH'd into the instance using `.pem` key
4. Installed Nginx  
   ```bash
   
## ✅ Project 2: S3 + CloudFront Static Website Hosting
A static website hosted in a private S3 bucket and delivered globally using CloudFront.

🛠️ Steps:
Created a basic index.html website

Made a private S3 bucket and uploaded files

Created a CloudFront distribution with the S3 bucket as origin

Enabled Origin Access Control (OAC)

Set index.html as root object

Accessed the live site via CloudFront URL
