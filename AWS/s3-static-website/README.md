AWS S3 Static Website — V1

Overview

A hands-on lab demonstrating how to host a static website using Amazon S3.

AWS Service

* Amazon S3 — Storage and static website hosting

Implementation

1. Created an S3 bucket.
2. Uploaded:
    * index.html
    * error.html
3. Enabled Static Website Hosting.
4. Configured:
    * Index document: index.html
    * Error document: error.html
5. Disabled Block Public Access for the bucket.
6. Created an S3 bucket policy allowing public GetObject access.
7. Tested the website through the S3 website endpoint.
8. Tested the custom error page by requesting a nonexistent URL.

Architecture

User
  │
  ▼
S3 Website Endpoint
  │
  ├── index.html
  └── error.html

Key Concepts

* S3 Static Website Hosting
* S3 Bucket Policy
* Public GetObject access
* Index and error documents

Screenshots

See the screenshots/ directory for implementation and testing evidence.

Files

index.html
error.html
