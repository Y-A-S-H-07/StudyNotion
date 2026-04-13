# 🚀 StudyNotion – EdTech Platform

A full-stack EdTech platform where users can browse, purchase, and learn courses online.
Built using the MERN stack with modern UI and real-world features like authentication, payments, and course management.

---

## 📌 Features

### 👤 User Features

* User Signup & Login (JWT Authentication)
* Email OTP Verification
* Browse Courses by Category
* Add to Cart & Purchase Courses
* Enroll and Track Course Progress
* View Enrolled Courses

### 👨‍🏫 Instructor Features

* Create & Manage Courses
* Upload Videos & Thumbnails
* Add Sections & Subsections
* Instructor Dashboard (earnings & students)

### 🛠️ Admin Features

* Manage Categories
* Control platform content

---

## 🧱 Tech Stack

### Frontend

* React.js
* Redux Toolkit
* Tailwind CSS
* React Router

### Backend

* Node.js
* Express.js

### Database

* MongoDB Atlas

### Services

* Cloudinary (Media Upload)
* Nodemailer (Email/OTP)
* Razorpay (Payments)

---

## ⚙️ Environment Setup

### 🔹 Frontend (.env)

```env
REACT_APP_BASE_URL=http://localhost:4000/api/v1
```

### 🔹 Backend (server/.env)

```env
MONGODB_URL=your_mongodb_atlas_url
JWT_SECRET=your_secret_key

CLOUD_NAME=your_cloud_name
API_KEY=your_api_key
API_SECRET=your_api_secret
FOLDER_NAME=studynotion

MAIL_HOST=smtp.gmail.com
MAIL_USER=your_email@gmail.com
MAIL_PASS=your_app_password

RAZORPAY_KEY=your_key
RAZORPAY_SECRET=your_secret
```

---

## ▶️ How to Run Locally

### 1. Clone Repository

```bash
git clone <your-repo-url>
cd studynotion-edtech-project-main
```

---

### 2. Install Dependencies

#### Frontend

```bash
npm install
```

#### Backend

```bash
cd server
npm install
```

---

### 3. Run Project

#### Start Backend

```bash
cd server
npm run dev
```

#### Start Frontend

```bash
npm start
```

---

### 4. Open in Browser

```
http://localhost:3000
```

---

## 📂 Project Structure

```
studynotion/
├── server/        # Backend (Node + Express)
├── src/           # Frontend (React)
├── components/    # UI Components
├── pages/         # Pages
├── services/      # API calls
├── redux/         # State management
```

---

## 🧪 API Example

```
GET /api/v1/course/showAllCategories
```

---

## 🚧 Future Improvements

* Add real payment flow (Razorpay live)
* Add admin dashboard UI
* Improve UI/UX animations
* Add search & filters
* Deploy on AWS/Vercel

---

## 👨‍💻 Author

Yash Dabhekar

---

## ⭐ If you like this project

Give it a star on GitHub ⭐
