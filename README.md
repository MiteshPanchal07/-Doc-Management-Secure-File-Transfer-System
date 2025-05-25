# Doc Management - Secure FileTransfer System

- Built a secure web application for encrypted document sharing and user-based file access using Python, Django, and Razorpay integration. The system includes user registration, login, 
and session-based authentication. Files can be uploaded as public, private, or user-privileged documents, with optional password protection using Django’s password hashing. It features cloud file storage, subscription-based access using custom packages, and real-time Razorpay payment gateway integration.

## 🚀 Features:
- Upload/download of documents with storage limits and expiry based on user package.
- Document sharing with access control and revocation via custom models.
- Password-protected private files.
- Recycle bin management for deleted files.
- Feedback and contact form handling.
- Payment tracking and validation using Razorpay.
- Cloud document upload and listing.
- Admin and user privilege logic with Django models.

## 🛠️ Tech Stack:
- Backend: Python, Django
- Security: Django Password Hashing (make_password, check_password)
- Payment Gateway: Razorpay Integration
- Database: Django ORM with SQLite
- File Handling: Django FileField for uploads, custom size/type detection
- Cloud Storage (local): CloudDocument model and views for document management
- Frontend Templates: HTML (rendered via Django)
- Others: Session Management, CSRF protection, Email field validation

## 📷 Screenshots:
![HomePage_](https://github.com/user-attachments/assets/9bd5b360-8058-4af1-bc79-a1283cf764a4)
![RegisterPage](https://github.com/user-attachments/assets/b8378211-5bcb-4ac9-aa74-314175654e87)
![LohinPage](https://github.com/user-attachments/assets/aa9abb43-7fa8-4033-8584-6b3951160125)
![UploadPublicly](https://github.com/user-attachments/assets/59a1ce1b-d3b2-44ad-9eca-089181982e50)
![UserPrivilege](https://github.com/user-attachments/assets/06c73a1a-0d90-4519-b1e2-96428087243d)
![UploadPrivately](https://github.com/user-attachments/assets/5086f108-e175-4ff3-bad7-d033adfdcb6f)
![ShareFiles](https://github.com/user-attachments/assets/a1e93f73-7b7c-48e5-807c-134f3e4aec13)
![PrivateFiles](https://github.com/user-attachments/assets/4e03cef5-7918-4ef6-95e0-7c4acea6fca6)
![RecycleBin](https://github.com/user-attachments/assets/deca695a-1c95-4737-98e5-67bc800001ce)
![PrimiumPlans](https://github.com/user-attachments/assets/e852393d-c21d-455c-8d88-f735efd41ed6)
![Payment Successfully)](https://github.com/user-attachments/assets/8fa0dbec-991f-406d-a8f4-3507bbac7590)








 
