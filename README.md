# AWS SAA Lab - Storage Architecture with Amazon S3

## Objective

Design and implement an enterprise-grade Amazon S3 storage architecture.

## Services Used

- Amazon S3
- IAM

## Storage Class Recommendations

| Workload | Storage Class |
|-----------|--------------|
| Website Images | S3 Standard |
| Application Logs | S3 Standard IA |
| Monthly Backups | Glacier Flexible Retrieval |
| Financial Records | Glacier Deep Archive |

## Security Controls

- Block Public Access Enabled
- IAM Permissions Applied
- Least Privilege Principle

## Key Learnings

- Object Storage vs Block Storage
- Durability vs Availability
- Lifecycle Management
- Storage Cost Optimization
- Governance and Compliance

