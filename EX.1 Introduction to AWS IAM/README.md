# Lab 1 - Introduction to AWS Identity and Access Management (IAM)

## Title
Introduction to AWS Identity and Access Management (IAM)


## Objective
The objective of this lab is to understand how AWS Identity and Access Management (IAM) controls authentication and authorization in AWS. The lab focuses on exploring IAM users and groups, analyzing attached policies, assigning users to appropriate groups based on organizational roles, and validating permissions by testing service access.


## Prerequisites
- Basic understanding of cloud computing concepts  
- AWS Academy Lab access  
- Web browser with internet connectivity  


## Tools Used
- AWS Management Console  
- AWS Identity and Access Management (IAM)  
- Amazon EC2  
- Amazon S3  


## Tasks Performed

### Task 1: Explore IAM Users and Groups
- Reviewed pre-created IAM users: user-1, user-2, user-3  
- Explored IAM groups: EC2-Admin, EC2-Support, S3-Support  
- Inspected managed and inline policies attached to groups  
**Screenshot:**  
<img width="1919" height="929" alt="Screenshot 2026-02-06 083214" src="https://github.com/user-attachments/assets/242705b5-578c-4963-9564-d92d852efef3" />

### Task 2: Add Users to Groups
- Added user-1 to the S3-Support group  
- Added user-2 to the EC2-Support group  
- Added user-3 to the EC2-Admin group  
**Screenshot:**  
<img width="1342" height="605" alt="Screenshot 2026-04-17 142028" src="https://github.com/user-attachments/assets/acfb3b41-a1a9-4079-814f-f417bfc53d64" />
<img width="1365" height="767" alt="Screenshot 2026-04-17 143001" src="https://github.com/user-attachments/assets/3e9ed45e-c907-41ff-91b6-73ca9ce34cbc" />
<img width="1170" height="493" alt="Screenshot 2026-04-17 141917" src="https://github.com/user-attachments/assets/646de1cb-092c-4428-9363-b42e83b0fd35" />





### Task 3: Test IAM User Permissions
- Logged in using IAM sign-in URL  
- Verified S3 access for user-1  
- Verified EC2 read-only access for user-2  
- Verified EC2 administrative access for user-3  
**Screenshot:**  
<img width="1365" height="732" alt="Screenshot 2026-04-17 193313" src="https://github.com/user-attachments/assets/2d90a5a6-4853-4d38-93f5-a8ac126b4d65" />



## Workflow
1. Accessed IAM console and reviewed users and groups.  
2. Inspected policy permissions attached to groups.  
3. Assigned users to groups based on their roles.  
4. Logged in as each IAM user using the sign-in URL.  
5. Validated permissions by accessing AWS services.  


## Learning Outcomes
- Understood the role of IAM in AWS security.  
- Learned how IAM users, groups, and policies interact.  
- Gained practical experience implementing role-based access control.  
- Verified permission enforcement through real-time service testing.  


## Conclusion
This lab provided hands-on experience with AWS IAM by demonstrating how organizations manage secure access to cloud resources. Assigning users to groups with predefined policies simplified permission management and ensured role-based access control across AWS services.


## Author
**Name:** R.SHIVAANI (212224220097)
