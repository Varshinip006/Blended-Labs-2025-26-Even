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

<img width="1263" height="747" alt="image" src="https://github.com/user-attachments/assets/e38b082a-102f-434b-93b4-8e75b89b8d94" />


### Task 2: Add Users to Groups
- Added user-1 to the S3-Support group  
- Added user-2 to the EC2-Support group  
- Added user-3 to the EC2-Admin group
  
**Screenshot:**  

<img width="1919" height="1199" alt="Screenshot 2026-02-24 101142" src="https://github.com/user-attachments/assets/3470dace-b5c4-4fd5-9528-93515e521e4c" />

<img width="1919" height="1199" alt="Screenshot 2026-02-24 101216" src="https://github.com/user-attachments/assets/3103639b-1ba2-4748-8e90-1c429c86c8de" />

<img width="1919" height="1199" alt="Screenshot 2026-02-24 101309" src="https://github.com/user-attachments/assets/ffa43a6a-9710-4101-b1d0-409656593a45" />


### Task 3: Test IAM User Permissions
- Logged in using IAM sign-in URL  
- Verified S3 access for user-1  
- Verified EC2 read-only access for user-2  
- Verified EC2 administrative access for user-3
  
**Screenshot:**

<img width="1919" height="1199" alt="Screenshot 2026-02-24 101655" src="https://github.com/user-attachments/assets/df2594b2-c8a9-4132-bd3b-2dbcdfe670f0" />

<img width="1919" height="1199" alt="Screenshot 2026-02-24 101745" src="https://github.com/user-attachments/assets/5966da24-a5e4-47cd-a4ea-ba11c5e7aa6a" />

<img width="1919" height="1199" alt="Screenshot 2026-02-24 102138" src="https://github.com/user-attachments/assets/b0ec99d3-c412-4c3a-865f-40992cd13908" />

<img width="1919" height="1199" alt="Screenshot 2026-02-24 102138" src="https://github.com/user-attachments/assets/f39fc64b-97ab-4158-97ae-bd8465c0a4ee" />

<img width="1919" height="1199" alt="Screenshot 2026-02-24 102430" src="https://github.com/user-attachments/assets/51ce2c5a-ea9d-447e-9e75-b58cb4287b7e" />

<img width="1919" height="1199" alt="Screenshot 2026-02-24 102851" src="https://github.com/user-attachments/assets/e1186091-d78d-4a65-869a-a157954e2514" />



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
**Name:** Priya Varshini P (212224240119)
**Course:** Introduction to Cloud Computing  

