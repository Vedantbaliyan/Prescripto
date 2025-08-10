# Prescripto 🩺
*A Doctor Appointment Application with User, Doctor, and Admin Portals*

---

## 🌐 Live Demo
- **User Portal:** [ https://prescriptobyvedantfrontend.onrender.com ](#)  
- **Doctor Portal:** [https://prescriptobyvedantadmin.onrender.com](#)  
- **Admin Portal:** [https://prescriptobyvedantadmin.onrender.com](#)  

## 📌 Overview
**Prescripto** is a full-stack Doctor Appointment Management application where users can:
- Create an account, log in, and book appointments with doctors of various specialties.
- Doctors can log in to manage and view their upcoming appointments.
- Admins can manage doctors, view all appointments, and cancel appointments if needed.

This project is built with **MongoDB, Node.js, Express, and React.js**. It features authentication, role-based portals, and is deployed via **Render** for frontend, backend, and admin portals.

---

## 🚀 Features
✅ **User Portal** – Register/Login, search doctors, book appointments, view bookings  
✅ **Doctor Portal** – Secure login, view/manage appointments  
✅ **Admin Portal** – Manage doctors, view/cancel appointments, add new doctors  
✅ **Authentication & Authorization** – JWT-based secure login for all portals  
✅ **Responsive UI** – Works on desktop & mobile  
✅ **Specialty Filtering** – Find doctors by their specialty  
✅ **Cloud Storage for Images** – Doctors can have profile pictures via Cloudinary  

---

## 🛠 Tech Stack
**Frontend:** React.js  
**Backend:** Node.js, Express.js  
**Database:** MongoDB  
**Authentication:** JWT (JSON Web Tokens)  
**Cloud Storage:** Cloudinary  
**Deployment:** Render  

---

## 📂 Project Structure
```
Prescripto/
│── backend/         # Node.js + Express + MongoDB API
│── frontend/        # React.js User Portal
│── admin/           # React.js Admin Portal
│── doctor/          # React.js Doctor Portal
│── README.md
```

---

## 💻 Local Setup
Follow these steps to run the project locally:

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/prescripto.git
cd prescripto
```

### 2️⃣ Install Dependencies
For **backend**:
```bash
cd backend
npm install
```

For **frontend**:
```bash
cd frontend
npm install
```

(Repeat for `admin` and `doctor` portals if separate.)

### 3️⃣ Environment Variables
Create a `.env` file in **backend** with:
```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
```

### 4️⃣ Run the Project Locally
Backend:
```bash
cd backend
npm start
```
Frontend:
```bash
cd frontend
npm start
```

---

## 📸 Screenshots
### Home Page
![Home Page](Screenshot 2025-08-10 130302.png)

### Doctor Search
![Doctor Search](Screenshot 2025-08-10 130321.png)

### Booking Appointment
![Booking Appointment](Screenshot 2025-08-10 130343.png)

### Doctor Portal
![Doctor Portal](Screenshot 2025-08-10 130415.png)

### Admin Dashboard
![Admin Dashboard](Screenshot 2025-08-10 130446.png)

---

## 📜 License
This project is licensed under the **MIT License**.
