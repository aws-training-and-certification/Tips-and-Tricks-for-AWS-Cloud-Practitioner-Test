# Tips and Tricks for AWS Cloud Practitioner Test

Since 2017, I've had [AWS certification] on my to-do list. Finally, the Covid-19 lockdown allowed me to work from home, and I discovered I was saving a lot of commuting time and made better use of my early time. After successfully launching a brand new project in the office in May 2020, I decided to pursue a few certifications.

[//]: # (Any comments)
[AWS certification]: <https://www.netcomlearning.com/vendors/aws-training.phtml?advid=1356>

Each quarter, AWS has grown by stratospheric proportions. Nothing else seemed more fitting for me than AWS. On May 25th, I scheduled an AWS cloud practitioner test for June 6th, and on the same day, I began studying. My teams have been creating products on AWS since 2016, but due to my job profile, I have not had much hands-on experience. However, I am familiar with the language and use cases. I believed that [AWS cloud practitioner certification] would strengthen my expertise.

[//]: # (Any comments)
[AWS cloud practitioner certification]: <https://www.netcomlearning.com/certification/aws-certified-cloud-practitioner/787/?advid=1356>

Here are a few examples of inquiries. 

•	AWS service that can host a Microsoft SQL Server database? (Select two)

•	Amazon EC2 is an abbreviation for Elastic Compute Cloud.

•	Amazon S3 is option B.

•	Amazon EBS is a type of cloud storage service.

•	RDS (Amazon Real-Time Delivery Service)

•	Amazon Aurora (E)

Option A is the correct choice since we can spin off an EC2 instance and install Microsoft SQL Server on top of it. However, this adds a significant amount of operational expense.
Option B is incorrect since S3 is the best option for object storage.
Option C: EBS stands for Enterprise Business Store. They are not intended for database hosting. As a result, this is not the correct response.
Option D: RDS (Relational Database Server) is unquestionably an option. RDS is compatible with PostgreSQL, MySQL, MariaDB, Oracle, and Microsoft SQL Server.
Aurora is a PostgreSQL and MySQL-compatible database. It is not a replacement or intended to be a replacement for Microsoft SQL Server.
As a result, we will select Options A and D.

One more thing:

### Ques: Your CTO wants to create a web application that is low-maintenance and scalable. What choices do you make?

Ans: Amazon EC2 for App Server, Amazon RDS for Web Server
Lambda, API Gateway, and Aurora Serverless are examples of B services.
C: Amazon EC2 with ASG for app server, Amazon EC2 for web server, Amazon Dynamo DB

D: Amazon EC2 with ASG for App Server, Amazon EC2 with ASG for Web Server, Amazon Dynamo DB
The critical words here are low maintenance and excellent scalability. If we want to meet both needs, EC2 is not the best option. As a result, we may proceed immediately to Option B, which is the correct decision.
