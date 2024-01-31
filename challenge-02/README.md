# DevOps Project Challenge: Static Site Deployment on AWS S3 with Route 53, HTTPS, and CloudFront Integration

## Overview
This challenge focuses on deploying a static website to AWS S3, setting up a custom domain with Route 53, securing the site with HTTPS, and distributing it globally via CloudFront.

## Detailed Instructions

### AWS S3 Static Website Hosting
- Create an S3 bucket for website hosting.
- Ensure the bucket policy allows public read access for static website hosting.

### Custom Domain Configuration with Route 53
- Purchase or use an existing domain within Route 53.
- Create a hosted zone and record sets to point to your S3 bucket.

### HTTPS Configuration
- Obtain an SSL/TLS certificate from AWS Certificate Manager (ACM).
- Ensure the certificate covers your domain and is validated.

### CloudFront Distribution Setup
- Create a CloudFront distribution.
- Point the origin to your S3 bucket's static website endpoint.
- Associate the ACM certificate with your CloudFront distribution to enable HTTPS.

### Expected Outcomes
By completing this challenge, you will deploy a secure, scalable static website on AWS, accessible via a custom domain. This demonstrates key DevOps skills in cloud resource management, static site deployment, and secure content delivery.

