## ☁️ AWS Cloud Infrastructure

SMRITI is deployed on Amazon Web Services (AWS) to provide a secure, scalable, and reliable cloud environment for memory care services and caregiver analytics.

### AWS Services Used

#### Amazon EC2
- Hosts the FastAPI backend application.
- Handles API requests, authentication, memory management, and recommendation logic.

#### Amazon EBS
- Provides persistent storage for application data and databases.
- Ensures data persistence even after instance restarts.

#### Amazon S3
- Stores memory-related photos, audio files, and backups.
- Provides scalable and durable object storage.

#### AWS IAM
- Manages secure access to AWS resources.
- Implements role-based access control.

#### Amazon VPC
- Creates a private and secure network environment.
- Protects communication between AWS resources.

## Architecture

User
│
▼
Frontend (HTML, CSS, JavaScript)
│
▼
AWS EC2 Instance (FastAPI Backend)
│
├── Amazon EBS
│   └── Database & Application Storage
│
└── Amazon S3
    └── Photos, Audio & Media Storage

Security Layer:
AWS IAM + Amazon VPC + Security Groups

## Cloud Features

- Secure cloud deployment on AWS
- Scalable backend hosting with EC2
- Persistent storage using EBS
- Media storage through Amazon S3
- Identity and access management through IAM
- Isolated networking using Amazon VPC