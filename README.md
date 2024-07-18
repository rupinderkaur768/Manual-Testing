# Manual-Testing Project
This repository contains the flow of test cases related to critical functionalities and the structure of defect documentation for a cloud computing application along with the deatils of Features on which I have worked as a Manual Tester.
# Project Details
|  Name | Description | Tools & Techniques Used |
|----------|----------|----------|
| Box | Box is a cloud-based platform that lets you securely store, manage, and share files. It's like having a digital filing cabinet accessible from your computer, phone, or tablet. You can collaborate with others on documents, control who sees your files, and even work on them offline. Think of it as a central hub for all your important documents. | - JIRA <br> - API <br> - Agile|
# Tested Features
|  Name | Description | Responsibilitites |
|----------|----------|----------|
| Box Sign | Box Sign is a secure, digital platform for sending and managing documents requiring electronic signatures. |To Test the Sign flows like <br> - Sent Request <br> - Received Request <br> - Sign Templates <br> - Batch Send <br> - CFR-Part11 <br> - Ready Sign Link |
| Box Annotations | Box Annotations lets you add comments, highlights, and drawings directly onto files for easy collaboration and feedback. |To Test the different Annotation Types for Image and Non Image files <br> - Comment Annotation <br> - Highlight Annotation <br> - Draw Annotation |
| Compliance Email | Compliance Email ensures that email communications adhere to legal and regulatory standards, protecting sensitive data and preventing legal risks. |To check the E2E flow of Emails between internal and external users <br>- Comment Email <br> - @Mention Email <br> - Task Email <br> - Collaboration Email|
| Data Retention | Data Retention defines how long data is stored for legal, business, or operational reasons. |To test the Retention Policies on Files and Folders|
| MFA | Box MFA adds an extra layer of security by requiring two forms of identification for account access. | To Test the security feature for Managed and External users <br> - TOTP Authentication <br> - SMS Authentication <br> - Email Authentication|
| Reports | Box Reports provide insights into user activity, content usage, and security for informed decision-making. |To Test the different types of Reports and it's generated data after GCP migration <br> - UAR (User Activity Report) <br> - User Statistics <br> - Files & Folders Report <br> - Security Report <br> - Collaboration Report|
