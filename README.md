# Task 06 - Host & Deploy Portfolio Website on AWS

## Overview
This project hosts a static portfolio website on AWS using S3 (static website hosting). Created CloudFront distribution to enable HTTPS and CDN caching.

## Steps performed
1. Created S3 bucket: `my-portfolio-joy-2025`
2. Enabled static website hosting (index.html)
3. Uploaded site files using `aws s3 sync`
4. Created CloudFront distribution for HTTPS + caching

## How to test
Open the site URL:
- CloudFront: https://dd2zdh50qc44a.cloudfront.net
