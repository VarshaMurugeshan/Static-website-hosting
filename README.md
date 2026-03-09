# AWS S3 Static Website Hosting with IAM Access Control

## Project Overview

This project demonstrates how to deploy a static portfolio website using **Amazon S3** while following AWS security best practices by using **IAM users instead of the root account**. The website files are uploaded to an S3 bucket, static website hosting is enabled, and a bucket policy is configured to allow public access.

## AWS Services Used

* **AWS Identity and Access Management (IAM)** – To manage users and permissions.
* **Amazon S3** – To store website files and host the static website.

## Project Architecture

IAM User → Amazon S3 Bucket → Static Website Hosting → Public Website Endpoint

## Steps Performed

### 1. IAM Setup

* Logged into the AWS console using an IAM user instead of the root account.
* Used IAM permissions to manage AWS resources securely.

### 2. Create S3 Bucket

* Navigated to Amazon S3 in the AWS Management Console.
* Created a new S3 bucket with a globally unique name.
* Selected the appropriate AWS region.

### 3. Upload Website Files

Uploaded static website files including:

* `index.html`
* `style.css`
* images
* resume file

### 4. Configure Public Access

* Disabled **Block Public Access** settings for the bucket.
* Configured a **bucket policy** to allow public read access for website files.

### 5. Enable Static Website Hosting

* Enabled **Static Website Hosting** in the S3 bucket properties.
* Set `index.html` as the index document.

### 6. Access the Website

* Used the **S3 website endpoint URL** to access the deployed portfolio website.

## Demo Video

Full deployment demonstration:

https://youtu.be/TVbtSsqGDVM

## Key Learning Outcomes

* Learned how to host static websites using Amazon S3.
* Understood IAM user management and AWS security best practices.
* Configured bucket policies and public access settings.
* Gained hands-on experience with cloud storage and website deployment.
