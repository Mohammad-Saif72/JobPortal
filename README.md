# Job Portal Application

A full-stack job portal application built with MERN stack (MongoDB, Express.js, React, Node.js) that connects job seekers with employers.

## Features

- User Authentication & Authorization
- Job Posting & Management
- Company Profiles
- Job Applications
- Resume Upload
- Search Functionality
- Real-time Updates

## Tech Stack

### Frontend
- React + Vite
- Redux Toolkit for state management
- Axios for API calls
- Cloudinary for file storage

### Backend
- Node.js & Express.js
- MongoDB with Mongoose
- JWT Authentication
- Cookie Parser
- CORS enabled

## API Endpoints

### User Routes
- `/api/v1/user` - User related operations

### Company Routes
- `/api/v1/company` - Company profile management

### Job Routes
- `/api/v1/job/post` - Post new jobs
- `/api/v1/job/get` - Get all jobs
- `/api/v1/job/getadminjobs` - Get admin jobs
- `/api/v1/job/get/:id` - Get specific job

### Application Routes
- `/api/v1/application` - Job application management

## Setup Instructions

1. Clone the repository
2. Install dependencies:
```bash:terminal
cd frontend && npm install
cd backend && npm install
