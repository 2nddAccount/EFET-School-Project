# EFET School Project

A role-based school management web application built to centralize student and academic operations in one place. The platform helps administrators, teachers, and students manage essential school information such as personal records, attendance, grades, payments, and messaging.

## Overview

EFET School Project was developed as a final school project to demonstrate a practical and secure school administration system. It provides different interfaces and permissions depending on the user role, making it easier to manage daily academic workflows and communication.

## Key Features

### Role-Based Access
The application supports three account types:

- **Admin**: Full access to manage users, approve registrations, assign roles, and oversee the system
- **Teacher**: Access to student academic data, attendance, grades, and messaging tools
- **Student**: Access to personal information, attendance records, grades, payments, and messages

### Core Modules
- Student personal information management
- Attendance tracking
- Grade management
- Payment tracking
- Internal messaging system
- User registration and approval workflow
- Admin notifications for new registrations
- Visitor account system with limited access until approval

### Visitor Approval Workflow
New users are created as visitors and initially have limited access. An administrator can then review and approve or reject the account. This improves security and ensures only verified users gain full access.

## Live Demo

You can try the application here:

[https://web-production-20d60.up.railway.app](https://web-production-20d60.up.railway.app)

## Demo Credentials

### Admin Account
- **Email:** admin@efet.ma
- **Password:** admin123

### Test Visitor Account
- **Email:** visitor@test.com
- **Password:** password123

> Note: Visitor accounts may require admin approval before gaining full access.

## How to Run Locally

The project can be launched with the following command:

```bash
cd /home/hattan/Desktop/Devlopmment/EFET-School-Project && source .venv/bin/activate && cd Efet_school_project/school_project && python main.py
```

## Technologies Used

- Python
- Flask
- Flask-Login
- Flask-SQLAlchemy
- SQLAlchemy
- PDFKit
- HTML, CSS, JavaScript
- Railway for deployment

## Project Purpose

This project was built to:

- Simplify school administration tasks
- Organize student data in one secure system
- Support communication between students, teachers, and administrators
- Demonstrate real-world web application development skills
- Implement role-based access control and approval workflows

## Latest Updates

- **Visitor Role System**: New users receive limited access until approved by an admin
- **Admin Notifications**: Real-time notifications for new registrations
- **User Management**: Approve/reject users, assign roles, and manage access
- **72-Hour Approval Process**: Visitors are informed about the approval timeline

## Project Structure

The main application is located in:

```bash
Efet_school_project/school_project
```

## License

This project was created for educational purposes.

## Contact

If you would like to learn more about this project, feel free to add your contact information here.
