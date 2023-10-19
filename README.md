# ONE-D: File Management Simplified!

## About the Project
OneDrive, abbreviated as "One-D," is a file management application aimed at simplifying file organization for users. This software tool facilitates seamless file navigation, updates, and deletions. As a cloud-based solution, it harnesses industry best practices from AWS, creating a highly scalable and dependable application that utilizes Amazon S3 and Amazon RDS to store user data. With its user-friendly interface and flexible features, One-D enhances digital file interactions, improving daily task efficiency and contributing to a more organized digital life.

This project was created for CMPE-281 - Cloud Technologies under the guidance of Prof. Sanjay Garge.

## Tech Stack
- Frontend: React
- Backend: Flask
- Cloud: AWS
- Database: MySQL

## Links
- [Video Link](https://youtu.be/5bL3pkgA6N4)
- [Website](https://one-d.cloud)

## Features
### User
1. Login
2. Signup with OTP verification (Cognito)
3. User File management page with upload/download/modify/edit (S3/RDS-MYSQL)
4. Logout
5. User month-end report emailed directly to the user (CloudWatch/lambda/SNS)

### Admin
1. Login
2. Progress bar with overall upload/delete/modified
3. Overall file control with delete option
4. Active user info
