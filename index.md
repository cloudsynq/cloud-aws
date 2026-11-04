# Cloud Computing — AWS

Start from nothing and build up to a system that stays online by itself. Every
chapter opens with the problem before the solution, then explains it with
diagrams, everyday analogies and a lab you can run yourself.

By **Sahil Kumar** · AWS Certified Solutions Architect – Associate

> **Keeping a copy.** Open any page and press **Ctrl + P**, then choose
> *Save as PDF*. Every page is set to print properly, so it reads the same on
> paper or offline. Nothing needs to be downloaded or installed to read it.

[Full syllabus, unit by unit](syllabus.html) · [Recommended books and docs](resources.md)

## Contents

### 00 · Introduction to Cloud Computing
What the cloud actually is, why it replaced buying servers, and the vocabulary
everything else in this volume assumes.

[Cloud introduction (PDF)](00-introduction/cloud-introduction.pdf) · [Terminology (PDF)](00-introduction/cloud-terminology.pdf)

### 01 · IAM — Identity &amp; Access Management
Who is allowed to do what. Users, groups, roles and policies, and why you stop
using the root account on day one.

[Theory notes](01-iam/theory-notes.html)

### 02 · EC2 — Elastic Compute Cloud
Renting a server by the hour. Instance types, images, key pairs, security groups
and the pricing models that decide your bill.

[Theory notes](02-ec2/theory-notes.html)

### 03 · EBS — Elastic Block Store
The disk attached to that server. Volume types, snapshots, encryption, and what
survives when an instance is terminated.

[Theory notes](03-ebs/theory-notes.html)

### 04 · S3 — Simple Storage Service
Storage without a server in front of it. Buckets, storage classes, versioning,
lifecycle rules and hosting a website straight out of a bucket.

[Theory notes](04-s3/theory-notes.html) · [Hands-on lab](04-s3/lab.html)

### 05 · VPC — Virtual Private Cloud
Your own private network inside AWS. Subnets, internet gateways, route tables
and the difference between a security group and a network ACL.

[Theory notes](05-vpc/theory-notes.html) · [Hands-on lab](05-vpc/lab.html) · [Screenshot walkthrough (PDF)](05-vpc/lab-guide.pdf)

### 06 · CloudWatch, CloudTrail &amp; SNS
Knowing what is happening, and who did it. Metrics, alarms, audit logs and
notifications — including why CloudWatch cannot see your server's memory.

[Theory notes](06-cloudwatch-cloudtrail-sns/theory-notes.html) · [Hands-on lab — an alarm that emails you](06-cloudwatch-cloudtrail-sns/lab.html)

### 07 · Elastic Load Balancing
One address in front of many servers. ALB against NLB, target groups, health
checks, and watching a broken server get taken out of rotation.

[Theory notes](07-elastic-load-balancing/theory-notes.html) · [Hands-on lab — build a load balancer](07-elastic-load-balancing/lab.html)

### 08 · Auto Scaling Groups
Capacity that follows demand. Launch templates, scaling policies, and the part
nobody expects — a dead server being replaced without anyone being told.

[Theory notes](08-auto-scaling/theory-notes.html)

## Still to Come

Auto Scaling lab · Route 53 · CloudFront · Amazon RDS · DynamoDB ·
AWS Lambda · Cost Explorer and billing

*New chapters are added after every class. Bookmark this page — the link never changes.*
