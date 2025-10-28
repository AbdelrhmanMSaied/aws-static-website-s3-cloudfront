# AWS Static Website Hosting with S3 and CloudFront


Project Overview
This project demonstrates how to deploy a static website on AWS using Amazon S3 for storage and Amazon CloudFront as a Content Delivery Network (CDN). The site is served globally with low latency, high security, and scalability.


Features
Static website hosted on S3 bucket
Public and secure access managed via bucket policies
Global content delivery through CloudFront
HTTPS enabled for secure traffic
Optional custom domain integration (not covered here)


Setup Steps
Created an S3 bucket configured for static website hosting.
Uploaded HTML and asset files to the S3 bucket.


Configured bucket policies to allow secure access:
Public read access for testing, or
Created a CloudFront distribution pointing to the S3 website endpoint.
Set Viewer Protocol Policy to redirect HTTP to HTTPS.
Tested the website using the CloudFront distribution URL.
