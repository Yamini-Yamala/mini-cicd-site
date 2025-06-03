# AWS Static Website with CI/CD using GitHub Actions

This project demonstrates a basic CI/CD pipeline to automatically deploy a static website to an AWS S3 bucket, using GitHub Actions and CloudFront.

## 🔧 Tools & Technologies Used

- *AWS S3* – For static website hosting  
- *AWS CloudFront* – For global content delivery  
- *GitHub Actions* – For CI/CD automation  
- *IAM* – Secure credentials and access  
- *HTML/CSS* – Static website content

## 🚀 CI/CD Workflow

Every time a change is pushed to the main branch:
1. GitHub Actions is triggered automatically.
2. It uploads the latest index.html to the specified S3 bucket.
3. CloudFront is used to serve the content globally.

## 🔐 Security & Permissions

- IAM Access Key & Secret are securely added to GitHub Secrets.
- Bucket policies are configured to allow public read access to the S3 site content.

## 📂 Project Structure

📁 aws-static-site-s3-cloudfront ├── index.html ├── .github │   └── workflows │       └── deploy.yml ├── README.md

## 🌐 Live Demo

CloudFront URL: [https://dofs4ue7kgvbh.cloudfront.net/]

---

## 📌 Learning Outcomes

- Created end-to-end CI/CD pipeline using GitHub Actions.
- Managed infrastructure deployment on AWS with best practices.
- Learned secure credential handling using GitHub Secrets.
