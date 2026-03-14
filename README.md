![background](AWS_ec2_ebs_project_images/bg_image.jpg)
# MariaDB-EBS-Resillience
Production-ready MariaDB database deployed on AWS EC2 with persistent EBS storage and automated snapshot backups. Includes full backup, data-loss simulation, and instant recovery — demonstrating real-world cloud resilience and disaster recovery skills.




**Production-Ready MariaDB Server on AWS**  
Deployed a highly reliable database for OnyxPay Ltd using EC2, EBS volumes, and snapshots — exactly as required in a real startup scenario.

## Project Overview
OnyxPay Ltd needed a database that **never loses data** even if the server crashes, supports regular backups, and allows instant recovery from accidental deletions.  

## Tools
- **EC2** (Amazon Linux 2)
- **EBS Volume** (separate persistent storage)
- **MariaDB** (data directory on EBS)
- **EBS Snapshots** (backup & recovery)

## Architecture
```
Application/User
↓
EC2 Instance (Amazon Linux)
↓
MariaDB Database
↓
Mounted EBS Volume (/var/lib/mysql)
↓
EBS Snapshot (Backup)
```
