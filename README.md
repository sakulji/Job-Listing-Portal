# Full Stack Job Portal

## Introduction

Full Stack Job Portal is a comprehensive web application that connects job seekers with employers. It provides a modern platform where job seekers can discover opportunities, apply for positions, and manage their applications, while employers can post job listings, track applicants, and manage their hiring process efficiently.

## Features

- **User Authentication**: Secure registration and login for both job seekers and employers using JWT tokens
- **Job Search & Discovery**: Browse and search job listings with advanced filtering options
- **Job Applications**: Apply for jobs online and track your application status in real-time
- **Application Management**: View detailed information about each application received
- **Bookmark Jobs**: Save interesting job postings for later review
- **Job Posting**: Employers can create, edit, and manage their job listings
- **Applicant Tracking**: Employers can view all applications for their posted jobs and manage applicant responses
- **Password Recovery**: Secure forget password functionality for account recovery
- **Responsive Design**: Fully responsive interface that works seamlessly on desktop and mobile devices
- **Real-time Updates**: Instant notifications and status updates for applications

## Technologies Used

### Frontend
- **Next.js** - React framework for production
- **React** - JavaScript library for building user interfaces
- **Redux** - State management for global application state
- **Tailwind CSS** - Utility-first CSS framework for styling
- **React Icons** - Icon library for UI components
- **React Data Table Component** - Advanced data table functionality
- **React Toastify** - Toast notifications
- **SWR** - Data fetching library

### Backend
- **Node.js** - JavaScript runtime environment
- **Express.js** - Web application framework
- **MongoDB** - NoSQL database
- **Mongoose** - MongoDB object modeling
- **JWT (JSON Web Tokens)** - Secure authentication
- **Bcryptjs** - Password hashing and encryption

### Development Tools
- **Tailwind CSS** - Styling framework
- **PostCSS** - CSS transformation
- **ESLint** - Code quality tool

## How to Run

### Prerequisites

Make sure you have the following installed on your system:
- Node.js (v14 or higher)
- npm (Node Package Manager)
- MongoDB (local or cloud instance)

### Installation & Setup

1. **Navigate to the project directory:**
   ```bash
   cd Full-Stack-Job-Portal-main
   ```

2. **Install all dependencies:**
   ```bash
   npm install
   ```

3. **Configure environment variables:**
   Create a `.env.local` file in the root directory and add:
   ```
   MONGODB_URI=mongodb://localhost:27017/job-portal
   JWT_SECRET=your_secret_key_here
   NEXT_PUBLIC_API_URL=http://localhost:3000
   ```

4. **Start MongoDB:**
   ```bash
   mongod
   ```

5. **Run the development server:**
   ```bash
   npm run dev
   ```

6. **Access the application:**
   Open your browser and go to `http://localhost:3000`

### Available Commands

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm start` - Start production server
- `npm run lint` - Run code linting