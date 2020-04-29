# AWS

## Concepts
- **IAM** : Identity and Access Management
- **OTP** : One Time Password
- **S3** : Simple Storage Service
  - It is a safe place to storage your files
  - It is Object-base storage
    - Objects consist of th following:
      - Key
      - Value
      - Version ID
      - Metadata
  - Files are storage in Buckets
  - Not suitable to install an operating system on
  - Protect the object with MFA Delete, to be safe that the object couldn't be deleted
  - S3 is universal namespace (the bucket name must be unique)
  - S3 Storage Classes
    - S3 Standard
    - S3 - IA (Infrequently Accessed) : Data that is accessed less frequently, but requires rapid access when needed.
    - S3 One Zone - IA
    - S3 Intelligent Tiering
    - S3 Glacier
    - S3 Glacier Deep Archive
- **EC2** : Elastic Compute Cloud
- **MFA** : Multi Factor Authentication


## Links
- [S3 FAQs](https://aws.amazon.com/s3/faqs/)
