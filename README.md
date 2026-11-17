# Virtual Courses – Learning Management System

Virtual Courses is a full-stack course management platform built using the MERN stack. It supports two types of users: students and instructors. Instructors can create and manage courses, while students can browse available courses, make payments, and enroll.

## Features

**User Authentication**
- JWT-based authentication with HttpOnly cookies.
- Google OAuth 2.0 login.
- Password hashing using bcrypt.
- OTP-based password recovery through Nodemailer.

**Course Management**
- Separate student and instructor roles.
- Instructors can create and manage courses.
- Students can browse courses and enroll in them.

**Payment Integration**
- Razorpay integration for course payments.
- Payment verification before enrollment.
- Automatic enrollment after successful payment.

**AI-Powered Course Search**
- Search for courses using text or voice input.
- Google Gemini API integration for course discovery.

## Tech Stack

- **Frontend:** React.js, Redux Toolkit, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JWT, Google OAuth 2.0, bcrypt
- **Payments:** Razorpay
- **Email:** Nodemailer
- **AI:** Google Gemini API

## Project Structure

```text
Virtual-Courses/
├── backend/
├── frontend/
├── .gitignore
└── README.md
```

## Getting Started

### Prerequisites
- Node.js and npm
- MongoDB
- Git

### Clone the repository

```bash
git clone https://github.com/Shubhang-09/Virtual-Courses.git
cd Virtual-Courses
```

### Install dependencies

Backend:
```bash
cd backend
npm install
```

Frontend:
```bash
cd frontend
npm install
```

### Environment Variables

Create the required environment configuration files for the frontend and backend.

The application requires configuration for services such as MongoDB, authentication, Google OAuth, Razorpay, email delivery, and Gemini API.

Keep all credentials and API keys in environment files. Never commit them to GitHub.

### Run Locally

Startup commands and environment variable names will be added after verifying the scripts and configuration in the frontend and backend.

## Acknowledgements

Original project by Sarthak Sood. Developed further with permission.

## Author

**Shubhang Joshi**

[GitHub](https://github.com/Shubhang-09)