# -Doc-Management-Secure-File-Transfer-System
Built a secure web application for encrypted document sharing and user-based file access using Python, Django, and Razorpay integration. The system includes user registration, login, and session-based authentication. Files can be uploaded as public, private, or user-privileged documents, with optional password protection using Django’s password hashing. It features cloud file storage, subscription-based access using custom packages, and real-time Razorpay payment gateway integration.

Included features like:

    Upload/download of documents with storage limits and expiry based on user package.

    Document sharing with access control and revocation via custom models.

    Password-protected private files.

    Recycle bin management for deleted files.

    Feedback and contact form handling.

    Payment tracking and validation using Razorpay.

    Cloud document upload and listing.

    Admin and user privilege logic with Django models.

Technologies Used:

    Backend: Python, Django

    Security: Django Password Hashing (make_password, check_password)

    Payment Gateway: Razorpay Integration

    Database: Django ORM with SQLite

    File Handling: Django FileField for uploads, custom size/type detection

    Cloud Storage (local): CloudDocument model and views for document management

    Frontend Templates: HTML (rendered via Django)

    Others: Session Management, CSRF protection, Email field validation

 preview: 
 ![Home Page](![HomePage_](https://github.com/user-attachments/assets/9bd5b360-8058-4af1-bc79-a1283cf764a4))
 ![Home Page](![HomePage_](https://github.com/user-attachments/assets/9bd5b360-8058-4af1-bc79-a1283cf764a4))
 
