# 🚀 StudyNotion - Online Education Platform

StudyNotion is a full-stack EdTech platform built using the MERN stack that enables instructors to create and manage courses while allowing students to discover, purchase, and learn from educational content online.

---

## 🌟 Features

### 👨‍🎓 Student Features

* User Registration & Login
* JWT Authentication & Authorization
* Email OTP Verification
* Browse Courses by Category
* Course Search & Discovery
* Add Courses to Cart
* Secure Course Purchase via Razorpay
* Enroll in Courses
* Track Course Progress
* Watch Course Videos
* Rate and Review Courses
* Manage Profile

### 👨‍🏫 Instructor Features

* Instructor Dashboard
* Create & Publish Courses
* Upload Course Thumbnails
* Upload Video Lectures
* Add Sections & Subsections
* Manage Course Content
* View Students Enrolled
* Track Earnings

### 🔐 Authentication Features

* JWT-based Authentication
* OTP Verification via Email
* Forgot Password Functionality
* Password Reset via Email

### ☁️ Media Management

* Cloudinary Integration
* Video Upload Support
* Image Upload Support

### 💳 Payment Integration

* Razorpay Payment Gateway
* Secure Checkout Flow
* Course Enrollment After Successful Payment

---

## 🏗️ System Architecture

StudyNotion follows a client-server architecture consisting of:

### Frontend

* React.js
* Redux Toolkit
* React Router
* Tailwind CSS

### Backend

* Node.js
* Express.js
* REST APIs
* JWT Authentication

### Database

* MongoDB Atlas
* Mongoose ODM

### Third-Party Services

* Cloudinary (Media Storage)
* Razorpay (Payments)
* Nodemailer (Emails & OTP)

---

## 🛠️ Tech Stack

### Frontend

* React.js
* Redux Toolkit
* Tailwind CSS
* React Icons
* React Hot Toast
* React Router DOM

### Backend

* Node.js
* Express.js
* JWT
* Bcrypt
* Mongoose
* Express File Upload

### Database

* MongoDB Atlas

### Cloud Services

* Cloudinary
* Razorpay
* Nodemailer

---

## 📂 Project Structure

```bash
StudyNotion
│
├── server
│   ├── config
│   ├── controllers
│   ├── middleware
│   ├── models
│   ├── routes
│   └── utils
│
├── src
│   ├── components
│   ├── pages
│   ├── services
│   ├── redux
│   ├── hooks
│   └── assets
│
└── public
```

---

## 🔑 Environment Variables

### Frontend (.env)

```env
REACT_APP_BASE_URL=http://localhost:4000/api/v1
REACT_APP_RAZORPAY_KEY=your_razorpay_key
```

### Backend (server/.env)

```env
PORT=4000

MONGODB_URL=your_mongodb_url

JWT_SECRET=your_jwt_secret

CLOUD_NAME=your_cloudinary_name
API_KEY=your_cloudinary_api_key
API_SECRET=your_cloudinary_secret
FOLDER_NAME=studynotion

MAIL_HOST=smtp.gmail.com
MAIL_USER=your_email@gmail.com
MAIL_PASS=your_app_password

RAZORPAY_KEY=your_razorpay_key
RAZORPAY_SECRET=your_razorpay_secret
```

---

## ⚙️ Installation & Setup

### 1. Clone Repository

```bash
git clone https://github.com/Y-A-S-H-07/StudyNotion.git
```

```bash
cd StudyNotion
```

### 2. Install Dependencies

Frontend

```bash
npm install
```

Backend

```bash
cd server
npm install
```

### 3. Start Backend

```bash
cd server
npm start
```

### 4. Start Frontend

```bash
npm start
```

### 5. Open Application

```bash
http://localhost:3000
```

---

## 📡 Core API Endpoints

### Authentication

```http
POST /api/v1/auth/signup
POST /api/v1/auth/login
POST /api/v1/auth/sendotp
POST /api/v1/auth/reset-password-token
POST /api/v1/auth/reset-password
```

### Courses

```http
POST /api/v1/course/createCourse
POST /api/v1/course/editCourse
GET  /api/v1/course/getAllCourses
GET  /api/v1/course/getCourseDetails
```

### Payments

```http
POST /api/v1/payment/capturePayment
POST /api/v1/payment/verifyPayment
```

---

## 📸 Key Functionalities

### Course Creation Flow

1. Instructor creates course
2. Upload thumbnail
3. Add sections
4. Add lectures/videos
5. Publish course

### Course Purchase Flow

1. Student adds course to cart
2. Razorpay checkout opens
3. Payment verification
4. Course enrollment
5. Course available in dashboard

---

## 🚀 Future Enhancements

* AI-powered course recommendations
* Course completion certificates
* Advanced analytics dashboard
* Admin management panel
* Course search filters
* Real-time notifications
* Live classes integration

---

## 👨‍💻 Author

**Yash Dabhekar**

* GitHub: https://github.com/Y-A-S-H-07
* LinkedIn: [www.linkedin.com/in/yash-dabhekar-568267284](http://www.linkedin.com/in/yash-dabhekar-568267284)

---

## ⭐ Support

If you found this project helpful, please give it a ⭐ on GitHub and share it with others.
