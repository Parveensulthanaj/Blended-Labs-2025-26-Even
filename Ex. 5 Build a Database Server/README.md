# Lab 5 – Build a Database Server (AWS)

## Author

* **Name**: PARVEEN SULTHANA J
* **Register Number**: 212224040233
* **Date of Submission**: 18-03-2026

---

## Objective

The objective of this experiment is to understand how to deploy and configure a database server in AWS. This lab focuses on launching an EC2 instance, installing a database management system (DBMS), configuring basic database settings, creating a sample database, and validating connectivity to the database server.

---

## Prerequisites

* Basic understanding of cloud computing concepts
* AWS account or AWS Academy Lab access
* An existing VPC and EC2 knowledge (from previous labs)
* Basic knowledge of Linux commands and SQL

---

## Tools Used

* AWS Management Console
* Amazon EC2
* Security Groups
* SSH Client (Terminal / PuTTY)
* MySQL / MariaDB / PostgreSQL (any one)

---

## Tasks Performed

### Task 1: Launch EC2 Instance for Database Server

Launch a new EC2 instance using Amazon Linux 2 AMI. Select an appropriate instance type and configure key pair and security group.

---

### Task 2: Configure Security Group for Database Access

Modify the security group to allow:

* SSH (Port 22) for remote access
* Database port (e.g., MySQL – 3306 or PostgreSQL – 5432)

---

### Task 3: Connect to EC2 Instance

Connect to the EC2 instance using SSH from your local machine.

---

### Task 4: Install Database Server

Install a database server software such as MySQL, MariaDB, or PostgreSQL on the EC2 instance using package manager commands.

---

### Task 5: Start and Configure Database Service

Start the database service and configure basic settings such as root password and user privileges.

---

### Task 6: Create a Sample Database

Create a sample database and a table inside it. Insert a few records into the table.

---

### Task 7: Test Database Connectivity

Test the database server by connecting to it locally or remotely and performing basic SQL queries.

---

## Workflow (Student Explanation)

1.Launched an Amazon Linux 2 EC2 instance with appropriate instance type, key pair, and security group.

2.Configured the security group to allow SSH (22) and database port (MySQL 3306/PostgreSQL 5432) access.

3.Connected to the EC2 instance via SSH from my local machine.

4.Installed a database server (MySQL/MariaDB/PostgreSQL) using package manager commands.

5.Started the database service, set root password, and configured user privileges.

6.Created a sample database and table, and inserted test records.

Verified database connectivity by executing basic SQL queries locally and remotely.
---

## Output Screenshots (Attach 3)

### Screenshot 1: EC2 Instance for Database Server

<img width="1920" height="1080" alt="cc6 1" src="https://github.com/user-attachments/assets/e125d111-a95f-459b-8a37-6e1e8e1585b3" />


---

### Screenshot 2: Database Service Running

<img width="1920" height="1080" alt="cc6 2" src="https://github.com/user-attachments/assets/1b74bcb1-9f39-4329-a9f3-a13eee6947e0" />
<img width="1920" height="1080" alt="cc6 3" src="https://github.com/user-attachments/assets/1235cd71-3de9-4047-a7b7-7c467e436f0e" />
<img width="1920" height="1080" alt="cc6 4" src="https://github.com/user-attachments/assets/faf3c5ef-25ea-4de9-994d-f3869c7d3898" />

---

### Screenshot 3: Sample Database and Table


<img width="1920" height="1080" alt="cc6 5" src="https://github.com/user-attachments/assets/e9581683-6051-4321-a0df-ff5808080a36" />

<img width="1920" height="1080" alt="cc6 6" src="https://github.com/user-attachments/assets/b453bbc8-4193-40f5-b6e0-aa3f1a1182bb" />


---

## Result

This experiment demonstrated how to build a database server in AWS using an EC2 instance. By installing and configuring a DBMS, creating a sample database, and testing connectivity, the fundamentals of hosting and managing a cloud-based database server were underst
