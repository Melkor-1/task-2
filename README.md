# AWS S3 Cloud-Based File Storage System

## Overview
This project demonstrates a **secure cloud-based file storage system** built using **Amazon S3**. It is designed to store, organize, and securely share intern-related documents such as joining letters and certificates using **private S3 buckets** and **Pre-Signed URLs**.

The project is beginner-friendly and focuses on real-world usage of AWS S3 with proper security practices.

## Features
- Secure file storage using Amazon S3  
- Organized document management using logical folders  
- Public access fully blocked  
- Temporary, secure file sharing using Pre-Signed URLs  

## Technologies Used
- **Cloud Provider:** Amazon Web Services (AWS)  
- **Service:** Amazon S3  
- **Tools:** AWS Management Console, AWS CLI  

## Security
- All files are **private by default**
- No public read or write access enabled
- Files are shared securely using **time-limited Pre-Signed URLs**

Example:
```bash
aws s3 presign s3://your-bucket-name/path/to/file.pdf --expires-in 3600
```

## Use Cases
* HR departments
* Internship management systems
* Educational institutions

## Key Learning
* Cloud storage fundamentals
* Secure access control in AWS S3
* Practical use of Pre-Signed URLs
* Applying cloud concepts to real-world scenarios

## Conclusion
This project provides a simple and effective implementation of a **secure and scalable cloud-based file storage system** using AWS S3, following best practices for security and organization.
