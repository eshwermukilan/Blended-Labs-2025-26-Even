# Lab 6 – Scale and Load Balance Your Architecture

## Title
Scale and Load Balance Your Architecture
```
Author : Eshwer M
Reg no : 212224040086
Date : 20-05-2026
```
---

## Objective

The objective of this lab is to understand how to design a scalable and highly available architecture on AWS using Auto Scaling and Elastic Load Balancing. This experiment focuses on distributing incoming traffic across multiple EC2 instances, automatically scaling resources based on demand, and validating fault tolerance.

---

## Prerequisites

* Basic knowledge of Amazon EC2 and VPC
* Completion of previous labs (IAM, EC2, EBS, Database Server)
* AWS Academy Lab access
* Stable internet connection

---

## Tools Used

* AWS Management Console
* Amazon EC2
* Elastic Load Balancer (ELB / ALB)
* Auto Scaling Groups (ASG)
* Amazon CloudWatch

---

## Tasks Performed

### Task 1: Review Existing Architecture

Students review the existing EC2-based application architecture created in previous experiments.

### Task 2: Create a Launch Template

Students create a launch template that defines the EC2 instance configuration including AMI, instance type, security group, and user data.

### Task 3: Create an Auto Scaling Group

Students create an Auto Scaling Group using the launch template and configure minimum, maximum, and desired instance capacity.

### Task 4: Configure an Application Load Balancer

Students create an Application Load Balancer and configure target groups for routing traffic to EC2 instances.

### Task 5: Register Auto Scaling Group with Load Balancer

Students attach the Auto Scaling Group to the target group of the load balancer.

### Task 6: Configure Scaling Policies

Students configure scaling policies based on CPU utilization using Amazon CloudWatch alarms.

### Task 7: Test Load Balancing and Scaling

Students test the setup by generating traffic and observing automatic scaling and load distribution.

---

## Workflow (To be filled by Student)

Describe step-by-step how you performed this experiment in your own words.

---

## Output Screenshots 
<img width="1920" height="1080" alt="Screenshot (7)" src="https://github.com/user-attachments/assets/8a9bc8f4-11fa-4062-b2f5-d796441678f3" />
<img width="1920" height="1080" alt="Screenshot (8)" src="https://github.com/user-attachments/assets/4a35fcb8-25c5-4933-b088-a85f3d5594e4" />
<img width="1920" height="1080" alt="Screenshot (9)" src="https://github.com/user-attachments/assets/cfc7c903-f961-4309-abe9-db9af923f5bd" />
<img width="1920" height="1080" alt="Screenshot (10)" src="https://github.com/user-attachments/assets/0efb9ef3-8713-428f-8c72-1d0714c7f44f" />
<img width="1920" height="1080" alt="Screenshot (11)" src="https://github.com/user-attachments/assets/9984f72f-538b-4610-8390-f872ad9d80fe" />
<img width="1920" height="1080" alt="Screenshot (14)" src="https://github.com/user-attachments/assets/cd16666b-0b38-4414-9ffb-c1a8ceab07c6" />
<img width="1912" height="900" alt="Screenshot 2026-03-12 215935" src="https://github.com/user-attachments/assets/0e1d0985-ca8e-435b-a5ad-dc52b372f2d0" />
<img width="1920" height="1080" alt="Screenshot (17)" src="https://github.com/user-attachments/assets/9f38e687-3eec-4eab-8baa-deb8ccf72f17" />

---


## Result

This experiment demonstrated how to build a scalable and fault-tolerant cloud architecture using Auto Scaling Groups and Elastic Load Balancing. The system automatically adjusted resources based on workload and ensured continuous service availability by distributing traffic across multiple instances.
