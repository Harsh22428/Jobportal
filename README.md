# Jobporal

**Jobporal** is a modern and scalable web application that connects job seekers with recruiters. It provides a seamless platform to search for jobs, apply with one click, manage applications, and post job openings.

## 🚀 Features

- 🔍 Advanced job search with filters
- 🧾 Resume upload & profile builder
- 📨 Apply to jobs in one click
- 🧑‍💼 Recruiter dashboard for managing postings & applications
- 📬 Email & in-app notifications
- 🔐 Secure authentication (JWT / OAuth)
- 🗓️ Application tracking system
- 📊 Admin dashboard with analytics

## 🛠 Tech Stack

**Frontend**  
- React.js  
- Tailwind CSS / SCSS  
- Redux / Context API  

**Backend**  
- Node.js  
- Express.js  
- MongoDB   
-  Mongoose ORM 

**Other Integrations**  
- Cloudinary (for image/resume uploads)  
- Nodemailer  

## 📦 Installation

### Prerequisites

- Node.js ≥ 18.x
- MongoDB 
- .env file with proper variables

### Clone and Setup

```bash
clone the repo
cd jobporal
npm install
# setup .env file
PORT=3000
MONGO_URI=your_mongodb_connection_string
SECRET_KEy=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

# Backend
cd server
npm run dev

# Frontend
cd client
npm run dev
```

## 📁 Project Structure

```bash
jobporal/
├── frontend/             
│   ├── public/         
│   └── src/           
│       ├── components/ 
│       ├── pages/      
│       └── utils/      
├── backend/             
│   ├── controllers/    
│   ├── models/         
│   ├── routes/         
│   └── utils/          
├── .env               
├── package.json        
└── README.md          

