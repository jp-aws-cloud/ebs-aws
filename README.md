# Amazon Elastic Block Store (Amazon EBS)

![Amazon Elastic Block Store (Amazon EBS)](img/image.png)

Amazon Elastic Block Store (Amazon EBS) provides scalable, high-performance block storage resources that can be used with Amazon Elastic Compute Cloud (Amazon EC2) instances. With Amazon Elastic Block Store, you can create and manage the following block storage resources:

- Amazon `EBS volumes` — These are storage volumes that you attach to Amazon `EC2` instances. After you attach a volume to an instance, you can use it in the same way you would use a local hard drive attached to a computer, for example to store files or to install applications.

- Amazon `EBS snapshots` — These are `point-in-time` backups of Amazon EBS volumes that persist independently from the volume itself. You can create snapshots to back up the data on your Amazon EBS volumes. You can then restore new volumes from those snapshots at any time.

## Features of Amazon EBS

Amazon EBS provides the following features and benefits:

- Multiple volume types — Amazon `EBS` provides multiple volume types that allow you to optimize storage performance and cost for a broad range of applications. 
Volume types are divided into two major categories: `1. SSD-backed storage` for transactional workloads, and `2. HDD-backed` storage for throughput intensive workloads.

- Scalability — You can create Amazon EBS volumes with capacity and performance specifications that meet your needs. As your needs changes, you can use Elastic Volumes operations to dynamically increase capacity or tune performance, with no downtime.

- Backup and recovery — Use Amazon EBS snapshots to back up the data stored on your volumes. You can then use those snapshots to instantly restore volumes or to migrate data across AWS accounts, AWS Regions, or Availability Zones.

- Data protection — Use Amazon EBS `encryption` to encrypt your Amazon EBS volumes and Amazon EBS snapshots. Encryption operations occur on the servers that host Amazon EC2 instances, ensuring the security of both data-at-rest and data-in-transit between an instance and its attached volume and subsequent snapshots.

- Data availability and durability — io2 Block Express volumes provide 99.999% durability with an annual failure rate of `0.001%`. Other volume types provide 99.8% to 99.9% durability with an annual failure rate of 0.1% to 0.2%. Additionally, volume data is automatically replicated across multiple servers in an Availability Zone to prevent the loss of data from the failure of any single component.

- Data archiving — EBS Snapshots Archive provides a low-cost storage tier to archive full, point-in-time copies of EBS Snapshots that you must retain for `90 days` or more for regulatory and compliance reasons, or for future project releases.

## Set up for Amazon EBS

### Tasks
1. Sign up for an AWS account
2. Create a user with administrative access
3. (Optional) Create and use a customer managed key for Amazon EBS encryption
4. (Optional) Enable block public access for Amazon EBS snapshots