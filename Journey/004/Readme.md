# Host a simple static webpage with AWS S3 and CloudFront

## Introduction

Amazon Simple Storage Service (Amazon S3) is an object storage service that offers industry-leading scalability, data availability, security, and performance. This means customers of all sizes and industries can use it to store and protect any amount of data for a range of use cases.

Amazon CloudFront is a web service that speeds up distribution of your static and dynamic web content, such as .html, .css, .js, and image files, to your users. CloudFront delivers your content through a worldwide network of data centers called edge locations. When a user requests content that you're serving with CloudFront, the request is routed to the edge location that provides the lowest latency (time delay), so that content is delivered with the best possible performance.

## Prerequisite

Have a AWS Account


## Cost
Free - The AWS S3 and CloudFront free tier would be sufficient.

## Difficulty

Intermediate

## Try yourself

### Step 1

Create a bucket in the Amazon S3 console and upload your website files.

### Step 2 

Create a web distribution in CloudFront.

### Step 3 

It is highly recommended that you use SSL (HTTPS) for your website. Select Custom SSL certificate to use a custom domain with HTTPS. To obtain a new certificate, select the Request certificate option. If you do not have a custom domain, you can still use HTTPS with the cloudfront.net domain for your distribution.

### Step 4 

Update your domain's DNS records to point your website's CNAME to the domain name of your CloudFront distribution.

### Step 5

Wait for your DNS changes to propagate and the previous DNS entries to expire

## Reference Materials

* [CloudFront Static Website](https://aws.amazon.com/premiumsupport/knowledge-center/cloudfront-serve-static-website/)
* [Hosting a static website using Amazon S3](https://docs.aws.amazon.com/AmazonS3/latest/userguide/WebsiteHosting.html)
