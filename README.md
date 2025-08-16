# 💻 JobFinder - MERN Stack Web App 🔍

**A full-stack job search platform** with AI-driven recommendations, real-time alerts, and seamless application tracking. Built with MongoDB, Express, React, and Node.js.  

---

## 🚀 Key Features  

- **🔍 Smart Job Search**: AI-powered recommendations based on your profile.  
- **📄 Resume Builder**: Create and upload resumes directly (PDF/DOCX support).  
- **💬 Real-time Chat**: Communicate with employers instantly.  
- **📌 Save & Track**: Bookmark jobs and track application statuses.  
- **🔔 Notifications**: Email & in-app alerts for new matches and deadlines.  

---

## 🛠️ Tech Stack  

### **Frontend**  
- **React.js** (with Hooks + Context API)  
- **Redux Toolkit** (State Management)  
- **Tailwind CSS** (Styling)  
- **Axios** (API Calls)  

### **Backend**  
- **Node.js** + **Express.js** (REST API)  
- **MongoDB** (Database)  
- **Mongoose** (ODM)  
- **JWT** (Authentication)  

### **Additional Tools**  
- **Firebase** (File Storage for Resumes)  
- **Socket.io** (Real-time Chat)  
- **Nodemailer** (Email Notifications)  

---

## 📦 Installation  

### **Prerequisites**  
- Node.js (v18+)  
- MongoDB Atlas (or local DB)  
- Git  

### **Steps**  
1. **Clone the repo**:  
   ```sh
   git clone https://github.com/Muskan-Seth03/JobFinder-App.git
   cd JobFinder-App

2. Install dependencies:

Backend
 ```sh
    cd backend && npm install  
```
Frontend
```sh
  cd ../frontend && npm install
```
3. Set up environment variables:

  Create a .env file in /backend:

```sh
.env

MONGO_URI=your_mongodb_atlas_uri
JWT_SECRET=your_jwt_secret_key
FIREBASE_API_KEY=your_firebase_config

```
# Run the app:
Backend (from /backend)
```sh
npm start  
```
Frontend (from /frontend)
```sh
npm start
```

# 🌐 Deployment
Deployed on Render (Backend) + Vercel (Frontend)
```
