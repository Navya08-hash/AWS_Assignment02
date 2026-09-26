# AWS_Assignment02
# Deploy a Static Portfolio Website on AWS

## Overview

This project demonstrates the deployment of a static portfolio website using AWS services. The project covers launching an EC2 instance, configuring a web server, creating an S3 bucket for static website hosting, and configuring public access.

## 1. Launch and Configure an EC2 Instance

### Tasks Completed

- Launched an Ubuntu EC2 instance on AWS.
- Connected to the instance.
- Installed and configured a web server.
- Hosted a simple static website on the EC2 instance.
- Verified that the website was accessible through the instance's public IP address.

### AWS Service Used

**Amazon EC2** — Used to provide a virtual Ubuntu server for hosting the website.

---

## 2. S3 Static Website Hosting

### Tasks Completed

- Created an Amazon S3 bucket.
- Uploaded HTML/CSS website files.
- Configured the bucket for static website hosting.
- Configured the required public access permissions.
- Tested the hosted website.

### AWS Service Used

**Amazon S3** — Used to store and serve the static website files.

---

## 3. Mini Project — Deploy a Static Portfolio Website on AWS

### Project Description

A simple portfolio website was created using HTML and CSS and deployed using AWS S3 static website hosting.

### Technologies Used

- HTML
- CSS
- Amazon S3
- Amazon EC2
- Ubuntu
- Apache/Nginx

### Deployment Flow

```text
HTML/CSS Portfolio
       ↓
    S3 Bucket
       ↓
Static Website Hosting
       ↓
   Public Access
       ↓
   Live Website
```

### Live Portfolio

My portfolio website can be viewed here:

**https://navyaworks.online**

### CloudFront

AWS CloudFront can optionally be configured in front of the S3 website to provide CDN-based content delivery and improve website performance for users in different geographic locations.

## Conclusion

This project provided hands-on experience with AWS EC2 and S3. I learned how to launch and configure an Ubuntu server, install a web server, host a simple website, configure S3 static website hosting, and deploy a static portfolio website using AWS.
