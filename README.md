# Job Portal

A full-stack Job Portal application built using the MERN stack (MongoDB, Express.js, React.js, Node.js). This platform allows users to search, filter, and apply for jobs, while companies can post job listings and manage applicants.

## Folder Structure

```text
JobPortal/
├── backend/       # Node.js + Express API
│   ├── controllers/
│   ├── middlewares/
│   ├── models/
│   ├── routes/
│   ├── utils/
│   ├── package.json
│   └── index.js
├── frontend/      # React.js client
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── hooks/
│   │   ├── redux/
│   │   ├── utils/
│   │   ├── App.jsx
│   │   └── main.jsx
│   ├── package.json
│   └── vite.config.js
├── .gitignore
└── README.md


markdown

---

## Features

### For Job Seekers
- Browse jobs by category, title, or location
- Search jobs using keywords
- Filter jobs by location, industry, and salary
- View job descriptions
- Apply for jobs

### For Companies / Admin
- Post new jobs
- View applicants for each job
- Manage company profiles

### Others
- Responsive design
- Smooth animations using Framer Motion
- State management with Redux Toolkit
- Persistent login using Redux Persist

---

## Technologies Used

**Frontend:**
- React.js
- Redux Toolkit
- Tailwind CSS
- Framer Motion
- Axios
- React Router

**Backend:**
- Node.js
- Express.js
- MongoDB (Mongoose)
- JWT for authentication
- dotenv for environment variables

**Others:**
- Redux Persist
- Cloudinary for file storage (if resumes/images uploaded)

---

## Getting Started

### Clone the Repository
```bash
git clone https://github.com/Pavankumar280/JobPortal.git
cd JobPortal
Backend Setup
bash
Copy code
cd backend
npm install
# Create a .env file with your MongoDB URI, JWT secret, etc.
npm run dev
Frontend Setup
bash
Copy code
cd frontend
npm install
npm start
API Endpoints (Backend)
POST /jobs – Create a job (Admin)

GET /jobs – Get all jobs (User)

GET /jobs/:id – Get job details by ID

GET /admin/jobs – Get jobs posted by admin

POST /auth/signup – User signup

POST /auth/login – User login

## Screenshots

### Homepage
![Homepage](https://res.cloudinary.com/dsmxl2q3j/image/upload/v1758472668/Screenshot_2025-09-21_220213_meyksv.png)

### Browse Jobs
![Browse Jobs](https://res.cloudinary.com/dsmxl2q3j/image/upload/v1758472668/Screenshot_2025-09-21_220245_cfxkxk.png)

### Job Details
![Job Details](https://res.cloudinary.com/dsmxl2q3j/image/upload/v1758472669/Screenshot_2025-09-21_220232_xzkqd3.png)

### Admin Dashboard
![Admin Dashboard](https://res.cloudinary.com/dsmxl2q3j/image/upload/v1758472867/Screenshot_2025-09-21_221041_nlmstx.png)


Contributing
Fork the repository

Create a new branch: git checkout -b feature/YourFeature

Commit your changes: git commit -m "Add some feature"

Push to the branch: git push origin feature/YourFeature

Create a pull request

License
This project is licensed under the MIT License.

Author
Pavankumar P. Sonune
GitHub: https://github.com/Pavankumar280
Email: pavansonune10@mail.com

yaml


