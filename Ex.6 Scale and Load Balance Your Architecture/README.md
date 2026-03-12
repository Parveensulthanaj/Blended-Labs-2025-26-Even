# Lab 6 – Scale and Load Balance Your Architecture

## Title

Scale and Load Balance Your Architecture
Author : PARVEEN SULTHANA J
Reg no : 212224040233
Date : 12-03-2026

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

<img width="1920" height="1080" alt="Screenshot (469)" src="https://github.com/user-attachments/assets/71de569d-bcbb-4c1c-ab86-3d087e8a36ff" />
<img width="1920" height="1080" alt="Screenshot (470)" src="https://github.com/user-attachments/assets/134b83c5-2eb4-4594-b593-2389a4df99a7" />
<img width="1920" height="1080" alt="Screenshot (471)" src="https://github.com/user-attachments/assets/e4339899-2f4f-4f2e-81c7-a98f2e7eafba" />
<img width="1920" height="1080" alt="Screenshot (472)" src="https://github.com/user-attachments/assets/f151406b-21fc-4ba3-9727-1e53d25365f7" />
<img width="1920" height="1080" alt="Screenshot (473)" src="https://github.com/user-attachments/assets/386c36ba-be84-46b8-84c8-c749cdcbe198" />
<img width="1920" height="1080" alt="Screenshot (474)" src="https://github.com/user-attachments/assets/99b1407b-0564-4bcb-a519-32b851d95759" />
<img width="1920" height="1080" alt="Screenshot (475)" src="https://github.com/user-attachments/assets/4982f49a-090e-467f-83bf-495bc5c1cf62" />
<img width="1920" height="1080" alt="Screenshot (476)" src="https://github.com/user-attachments/assets/173a5a69-5026-43e6-b93a-4cb774a465a7" />
<img width="1920" height="1080" alt="Screenshot (477)" src="https://github.com/user-attachments/assets/9625f2ec-a9ff-4e24-8236-fb5716a5e1d6" />
<img width="1920" height="1080" alt="Screenshot (481)" src="https://github.com/user-attachments/assets/237759b5-1fe6-48cf-952a-7d00303f91a0" />

---


## Result

This experiment demonstrated how to build a scalable and fault-tolerant cloud architecture using Auto Scaling Groups and Elastic Load Balancing. The system automatically adjusted resources based on workload and ensured continuous service availability by distributing traffic across multiple instances.
