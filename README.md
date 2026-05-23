# AWS Static Website Hosting using Amazon S3 + CloudFront

## Project Overview

This project demonstrates secure static website hosting using Amazon S3 and Amazon CloudFront.

The architecture follows AWS security best practices by keeping the S3 bucket private while allowing CloudFront secure access.

## Architecture

```
User
 ↓ HTTPS
CloudFront CDN
 ↓
Private Amazon S3 Bucket
(index.html + style.css)
```

## AWS Services Used

- Amazon S3
- Amazon CloudFront
- IAM Security Principles

## Features

- Secure HTTPS delivery
- Global CDN distribution
- Private S3 bucket architecture
- Static website hosting
- Low-cost cloud deployment
- AWS security-first design

## Project Implementation Steps

1. Created Amazon S3 bucket
2. Uploaded website files
3. Configured CloudFront distribution
4. Enabled secure private S3 access
5. Implemented HTTPS delivery
6. Deployed globally

## Screenshots

### Live Website

Add screenshot here

### CloudFront Distribution

Add screenshot here

### S3 Bucket

Add screenshot here

## Skills Demonstrated

AWS • S3 • CloudFront • CDN • IAM • HTTPS • Cloud Security • Static Website Hosting

## Cost Optimization

Built using AWS Free Tier eligible services with cost-aware architecture.

## Author

Shubh Palsetkar

AWS Certified Solutions Architect Associate
