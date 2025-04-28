# Student Productivity & Attendance Tracker

## Overview
A cloud-based web application designed for training institutes to manage student attendance, feedback, and course enrollment efficiently. Built with React.js and AWS serverless technologies.

## Key Features

### Student Features
- 📝 **User Registration**: Secure sign-up with auto-generated NCT-IDs (e.g., NCT-CYS-001)
- ✅ **Attendance Tracking**: Log in/out of classes with timestamps
- 💬 **Feedback System**: Submit course feedback (anonymous option available)
- 📅 **Class Schedule**: View upcoming sessions and notifications
- 🎓 **Course Registration**: Enroll in programs with payment status tracking

### Admin Features
- 📊 **Attendance Reports**: Daily/weekly analytics
- 🔍 **Feedback Review**: View and analyze student feedback
- 👥 **User Management**: Monitor student accounts and enrollment

## Technology Stack

### Frontend
- html, css, js
- AWS S3 (Hosting)
- CloudFront (CDN)

### Backend
- AWS Lambda (Serverless functions)
- API Gateway (REST API)
- DynamoDB (Database)
- IAM (Security)

## Installation

### Prerequisites
- Node.js (v16+)
- AWS account
- AWS CLI configured

### Setup
1. Clone repository:
   ```bash
   git clone [repository-url]
   cd student-attendance-tracker
   ```

## Deployment
The application is designed for serverless deployment on AWS:
- Frontend hosted on S3 + CloudFront
- Backend using Lambda and API Gateway
- Database in DynamoDB

## Usage
1. Access the web application at the deployed URL
2. Register as a student or admin
3. Use the dashboard to:
   - Log attendance
   - Submit feedback
   - View schedules
   - Manage courses (admin only)

## License
MIT License

## Contact
For support or contributions, please contact [your-email@example.com]
