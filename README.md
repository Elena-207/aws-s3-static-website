# AWS S3 Static Website Hosting

This project demonstrates how to host a simple static website using Amazon S3.

## What I Built

I created an S3 bucket, uploaded an `index.html` file, enabled static website hosting, and configured a bucket policy to allow public read access.

## AWS Services Used

- Amazon S3
- S3 Static Website Hosting
- Bucket Policy / IAM-style JSON permissions

## Key Concepts Learned

- S3 buckets store objects such as HTML files
- Static website hosting allows S3 to serve website files directly
- Hosting and permissions are separate concepts
- Bucket policies control who can access files
- `s3:GetObject` allows public users to read objects from the bucket

## Architecture

Browser → S3 Bucket → index.html

## Project Result

A simple static website hosted publicly using Amazon S3.
