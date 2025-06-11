# Amazon EBS (Elastic Block Store)

## Overview
Amazon EBS provides persistent block storage volumes for use with Amazon EC2 instances. Each EBS volume is automatically replicated within its Availability Zone to protect you from component failure.

## Key Features
- Persistent, high-performance block storage
- Snapshots for backup and disaster recovery
- Encryption at rest and in transit
- Multiple volume types (General Purpose, Provisioned IOPS, etc.)
- Easily scalable and resizable

## Common Use Cases
- Boot volumes for EC2 instances
- Database storage
- Enterprise applications
- Backup and restore

## Example Usage
1. Create an EBS volume and attach it to an EC2 instance.
2. Format and mount the volume on your instance.
3. Take snapshots for backup or migration.
4. Resize or change the volume type as needed.

## Documentation
- [Amazon EBS Documentation](https://docs.aws.amazon.com/ebs/)
