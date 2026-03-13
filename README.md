![background](AWS_ec2_ebs_project_images/bg_image.jpg)
# MariaDB-EBS-Resillience
Production-ready MariaDB database deployed on AWS EC2 with persistent EBS storage and automated snapshot backups. Includes full backup, data-loss simulation, and instant recovery — demonstrating real-world cloud resilience and disaster recovery skills.



[![AWS](https://img.shields.io/badge/AWS-EC2%20%7C%20EBS%20%7C%20MariaDB-FF9900?style=for-the-badge&logo=amazonaws)](https://aws.amazon.com)
[![MariaDB](https://img.shields.io/badge/MariaDB-Database-1F3054?style=for-the-badge&logo=mariadb)](https://mariadb.org)

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
