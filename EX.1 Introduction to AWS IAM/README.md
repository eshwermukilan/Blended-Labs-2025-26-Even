# Lab 1 - Introduction to AWS Identity and Access Management (IAM)
## Author
```
NAME : ESHWER M
REG NO : 212224040086
SLOT NO : 25EV2038
COURSE: INTRODUCTION TO CLOUD COMPUTING
```
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
<img width="1920" height="1200" alt="Screenshot (128)" src="https://github.com/user-attachments/assets/93c1f421-3f5e-4215-b24d-7570ffcd9ecc" />
<img width="1920" height="1200" alt="Screenshot (129)" src="https://github.com/user-attachments/assets/2be6339e-ea65-4d4b-b1d5-4c58602a2c55" />
<img width="1920" height="1200" alt="Screenshot (130)" src="https://github.com/user-attachments/assets/7c59efa9-5f4c-4589-814c-c798f1251f20" />


### Task 2: Add Users to Groups
- Added user-1 to the S3-Support group  
- Added user-2 to the EC2-Support group  
- Added user-3 to the EC2-Admin group
**Screenshot:**  
<img width="1920" height="1200" alt="Screenshot (125)" src="https://github.com/user-attachments/assets/da0b3973-012e-40e2-9f11-ad71097e640f" />
<img width="1920" height="1200" alt="Screenshot (126)" src="https://github.com/user-attachments/assets/c23f2008-e26b-4ac3-a92b-e42d5b5c7283" />
<img width="1920" height="1200" alt="Screenshot (127)" src="https://github.com/user-attachments/assets/1ec952b0-1dd0-43c5-a544-ce2ec451ce8f" />


### Task 3: Test IAM User Permissions
- Logged in using IAM sign-in URL  
- Verified S3 access for user-1  
- Verified EC2 read-only access for user-2  
- Verified EC2 administrative access for user-3  
**Screenshot:**  
### USER-1 :
<img width="1920" height="1200" alt="Screenshot (131)" src="https://github.com/user-attachments/assets/e7aa6239-fc50-42a5-ba32-bb88ae3055a8" />
<img width="1920" height="1200" alt="Screenshot (132)" src="https://github.com/user-attachments/assets/0bcf002a-f9f0-47ac-b458-5df62f284bf7" />

### USER-2 :
<img width="1920" height="1200" alt="Screenshot (133)" src="https://github.com/user-attachments/assets/0b3952bc-7b8d-4a0e-b467-843c640b1751" />

### USER-3 :
<img width="1920" height="1200" alt="Screenshot (135)" src="https://github.com/user-attachments/assets/248e7da7-c0ab-4e69-9e68-16531f35b0f7" />


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
