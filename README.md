# Job Portal

A full-stack job portal application built with a modern tech stack, allowing users to register, browse job listings, and apply for jobs, while employers can post job opportunities and manage applications. The application features user authentication, role-based profiles, and file uploads for resumes and company logos.

## Features

- **User Authentication**: Register and log in as a Student or Employer with role-based access.
- **Job Listings**: Browse and search for job opportunities with filtering options.
- **Job Applications**: Apply to jobs by uploading resumes (PDF format).
- **Employer Dashboard**: Post and manage job listings, view applications.
- **File Uploads**: Upload profile pictures and resumes using Cloudinary.
- **Responsive Design**: Built with Tailwind CSS for a mobile-friendly UI.
- **Tech Stack**:

**Frontend**:
- React.js (with Vite for fast development)
- Tailwind CSS for styling
- Redux Toolkit for state management)
- Axios for API requests
- React Router for client-side routing
- **Backend**:
- Node.js with Express.js
- MongoDB for data storage
- Mongoose for ODM
- Cloudinary for file uploads
- JWT for authentication
- Multer for handling multipart/form-data
- **Tools**:
  - Vite for frontend build
  - PostCSS and Autoprefixer for CSS processing
  - ESLint for code linting
  - Prerequisites

  - Node.js** (v18.x or later)
  - npm** (v8.x or later) or Yarn
  - MongoDB** (running locally or cloud instance)
  - Cloudinary** account for file uploads
  ## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/job-portal.git
cd job-portal

PORT=
MONGO_URI=mongodb://localhost:27017/jobportal
CLOUD_NAME=your_cloudinary_cloud_name
API_KEY=your_cloudinary_api_key
API_SECRET=your_cloudinary_api_secret
SECRET_KEY=your_jwt_secret
