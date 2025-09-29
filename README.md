# AWS S3 Lab 3c - Boto3

This repository contains Python scripts for Lab 3c of Cloud Computing (AWS S3 with Boto3).

## Scripts
- create_bucket.py – Creates an S3 bucket.
- upload_file.py – Uploads a file to the bucket.
- download_file.py – Downloads a file from the bucket.
- delete_file.py – Deletes a file from the bucket.
- enable_versioning.py – Enables versioning on the bucket.
- delete_bucket.py – Deletes the bucket (bucket must be empty).
- (Optional) nuke_bucket.py – Empties and deletes a versioned bucket.

## How to Run
```bash
python create_bucket.py
python upload_file.py
python download_file.py
python delete_file.py
python enable_versioning.py
python delete_bucket.py
```

## Notes
- Run inside a Python virtual environment (boto3_env).
- Make sure AWS CLI is configured with `aws configure`.
- Do not commit AWS credentials or sensitive files.

## Author
Gayatri Thakur

