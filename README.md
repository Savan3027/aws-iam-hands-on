# Task 1: IAM User with S3 Read Only Access

## Objective
To understand IAM users, policies, and the least privilege principle.

## What I did
- Created an IAM user
- Attached AmazonS3ReadOnlyAccess policy
- Logged in using the IAM user
- Accessed Amazon S3

## Verification
- Able to list S3 buckets
- Able to open a bucket
- Able to view folders and files
- Not able to upload or delete files

## Learning
- IAM user represents a human identity
- Default permission is deny
- Read-only access follows least privilege
