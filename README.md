# 🎬 CineBook: Movie Booking Ecosystem

![MERN Stack](https://img.shields.io/badge/Stack-MERN-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![UI](https://img.shields.io/badge/UI-Cinematic-red.svg)

**CineBook** is a premium, production-grade Movie Ticket Booking platform built with the MERN stack. It features a cinematic, Netflix-inspired user interface, a robust administrative control center, and a seamless QR-based ticket verification system designed for real-world theater operations.

---

## 🌟 Key Pillars

### 🎥 1. Cinematic User Experience
*   **Netflix-Inspired UI**: A high-end dark aesthetic with glassmorphic elements and professional typography.
*   **Immersive Hero Section**: Dynamic "Ken Burns" effect sliders with smooth cross-fading transitions.
*   **Interactive Movie Catalog**: Staggered entrance animations (`framer-motion`), real-time search, and genre filtering.
*   **Modern Seat Selection**: A category-based interactive grid (Balcony, Gold, Silver) with real-time price calculation.

### 🛡️ 2. Administrative Control Center
*   **Authorized Bypass Access**: Secure administrative entry via a standard bypass mechanism (`123456`).
*   **Full CRUD Management**: Comprehensive dashboards to manage Movies, Shows, Snacks, and Parking lots.
*   **Real-time Analytics**: Visual data tracking for ticket sales, revenue generation, and theater occupancy.
*   **Theater-Specific Assets**: Assign unique snacks and parking pricing to individual theaters.

### 🎟️ 3. Smart Ticketing & Entry
*   **QR Code Generation**: Every booking generates a unique, encrypted QR code for security.
*   **Public Verification System**: A dedicated, login-free entry portal for theater staff to scan and verify tickets instantly.
*   **Ticket Lifecycle**: Automatic status tracking (VALID → USED → COMPLETED) to prevent double entry.
*   **Digital Downloads**: High-quality PDF ticket generation for offline use.

---

## 🛠 Tech Stack & Architecture

### **Frontend (The Experience)**
- **React.js**: Functional components with Hooks and Context API.
- **Framer Motion**: High-performance cinematic animations and transitions.
- **Tailwind CSS**: Modern glassmorphic design system.
- **Axios**: Centralized API management with custom interceptors for authentication.
- **QRCode.react**: Dynamic QR generation.
- **jsPDF & html2canvas**: Client-side ticket rendering.

### **Backend (The Engine)**
- **Node.js & Express.js**: Modular REST API architecture.
- **MongoDB & Mongoose**: Relational data modeling in a NoSQL environment.
- **JWT Authentication**: Secure user sessions.
- **Security Middleware**: Role-based access control (RBAC) and admin bypass logic.

---

## 📂 Project Structure

```bash
Movie-Booking-System-MERN/
├── client/                 # React Frontend (Vite/CRA)
│   ├── src/
│   │   ├── api.js         # Centralized API Interceptor
│   │   ├── pages/         # Cinematic UI Pages
│   │   ├── components/    # Reusable UI Atoms
│   │   └── App.js         # Routing & Global State
│   └── package.json
│
├── server/                 # Node.js Backend
│   ├── controllers/       # Business Logic
│   ├── models/            # Database Schemas
│   ├── routes/            # API Endpoints
│   ├── middleware/        # Security & Auth Logic
│   └── server.js          # Entry Point
│
└── README.md
```

---

## ⚙️ Setup & Installation

### **1. Clone the Repository**
```bash
git clone https://github.com/VishalSudhaArul/Movie-Booking-System-MERN.git
cd Movie-Booking-System-MERN
```

### **2. Backend Configuration**
```bash
cd server
npm install
```
Create a `.env` file in the `server` directory:
```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secure_secret_key
PORT=5000
```
Start the server:
```bash
npm start
```

### **3. Frontend Configuration**
```bash
cd ../client
npm install
```
Create a `.env` file in the `client` directory:
```env
REACT_APP_API_URL=http://localhost:5000
```
Start the application:
```bash
npm start
```

---

## 🔐 Admin Access
To access the Administrative Dashboard without a theater-owner account:
1. Navigate to the **Admin** link in the navbar.
2. Enter the authorized bypass password: `123456`.
3. You will be granted full CRUD privileges for the session.

---

## 👨‍💻 Author
**Shubham Jadhav**  
*Full Stack Developer *

---
## 👨‍💻 SCREENSHOTS

<img width="1912" height="911" alt="image" src="https://github.com/user-attachments/assets/e6929446-8c54-44cb-9d8c-ca55b960d13e" />

<img width="1897" height="907" alt="image" src="https://github.com/user-attachments/assets/8ac90a3f-96ca-4a27-b41e-128b61423267" />

<img width="1885" height="905" alt="image" src="https://github.com/user-attachments/assets/42135c1e-f5f9-437a-940c-04e034dec93e" />

<img width="1855" height="902" alt="image" src="https://github.com/user-attachments/assets/8d8e0703-fdee-43b5-91aa-de05e56d1479" />

<img width="1743" height="916" alt="image" src="https://github.com/user-attachments/assets/203c9a6d-3a7a-47d6-a99f-f6e0febef3c1" />

<img width="1540" height="916" alt="image" src="https://github.com/user-attachments/assets/8aad8831-f1a8-4b7b-89c0-aa5f30568a8e" />

<img width="1908" height="895" alt="image" src="https://github.com/user-attachments/assets/0e614067-3fc5-4f6d-abf6-2d267194f428" />

<img width="1832" height="908" alt="image" src="https://github.com/user-attachments/assets/e7b9ab14-fd0c-4e20-a20a-1c050d7a1904" />

<img width="993" height="835" alt="image" src="https://github.com/user-attachments/assets/f1a2beaa-9723-4471-879c-f90594ce37a6" />


## ADMIN DASHBOARD

<img width="1871" height="907" alt="image" src="https://github.com/user-attachments/assets/a451a2d0-ce07-4b45-a2b8-ba3f349d2211" />

<img width="1876" height="907" alt="image" src="https://github.com/user-attachments/assets/9d957a89-7d83-4caa-9e52-9779fa420e28" />

<img width="1872" height="912" alt="image" src="https://github.com/user-attachments/assets/d1df6228-c88f-4cea-84f0-21fda8f62b53" />

<img width="1882" height="910" alt="image" src="https://github.com/user-attachments/assets/9e5b536f-773b-42c2-93cb-609efdde2ef1" />

<img width="1860" height="906" alt="image" src="https://github.com/user-attachments/assets/b9870f48-121a-42ae-8e0b-f533ff16d053" />

<img width="1883" height="908" alt="image" src="https://github.com/user-attachments/assets/d4338a3a-0d2b-41fb-b09b-bebd2c81e1f1" />

<img width="1875" height="916" alt="image" src="https://github.com/user-attachments/assets/4195fa7b-c34c-4852-8645-a4b675d19645" />

<img width="1878" height="912" alt="image" src="https://github.com/user-attachments/assets/63f58c8d-63c7-44a2-b30c-8ebbfef19e02" />

<img width="1872" height="905" alt="image" src="https://github.com/user-attachments/assets/cd56bad1-cddd-448f-9a19-5e63d315573d" />

<img width="1842" height="907" alt="image" src="https://github.com/user-attachments/assets/73409498-a22b-4251-b325-e5bd42ade8e0" />

<img width="1838" height="906" alt="image" src="https://github.com/user-attachments/assets/55f5116e-3948-4dcd-b783-f3c8e45f5fbc" />

<img width="1850" height="900" alt="image" src="https://github.com/user-attachments/assets/a72fc89a-1691-46fb-b5be-47c12afaafeb" />

<img width="1855" height="898" alt="image" src="https://github.com/user-attachments/assets/017d6270-50c7-435a-b270-ed355292848d" />


## 👨‍💻 User Interface

### 🏠 Home Page
<img width="1912" height="911" alt="Home Page" src="https://github.com/user-attachments/assets/e6929446-8c54-44cb-9d8c-ca55b960d13e" />

### 🎬 Movies Listing
<img width="1897" height="907" alt="Movies Listing" src="https://github.com/user-attachments/assets/8ac90a3f-96ca-4a27-b41e-128b61423267" />

### 🎥 Movie Details
<img width="1885" height="905" alt="Movie Details" src="https://github.com/user-attachments/assets/42135c1e-f5f9-437a-940c-04e034dec93e" />

### 🪑 Seat Selection
<img width="1855" height="902" alt="Seat Selection" src="https://github.com/user-attachments/assets/8d8e0703-fdee-43b5-91aa-de05e56d1479" />

### 🍿 Snacks & Add-ons
<img width="1743" height="916" alt="Snacks and Add-ons" src="https://github.com/user-attachments/assets/203c9a6d-3a7a-47d6-a99f-f6e0febef3c1" />

### 🚗 Parking Reservation
<img width="1540" height="916" alt="Parking Reservation" src="https://github.com/user-attachments/assets/8aad8831-f1a8-4b7b-89c0-aa5f30568a8e" />

### 📅 My Bookings
<img width="1908" height="895" alt="My Bookings" src="https://github.com/user-attachments/assets/0e614067-3fc5-4f6d-abf6-2d267194f428" />

### 🎟️ Ticket Verification
<img width="1832" height="908" alt="Ticket Verification" src="https://github.com/user-attachments/assets/e7b9ab14-fd0c-4e20-a20a-1c050d7a1904" />

### 📱 QR Code Scanner
<img width="993" height="835" alt="QR Code Scanner" src="https://github.com/user-attachments/assets/f1a2beaa-9723-4471-879c-f90594ce37a6" />

---

# 🛠️ Admin Dashboard

### 📊 Dashboard Overview
<img width="1871" height="907" alt="Dashboard Overview" src="https://github.com/user-attachments/assets/a451a2d0-ce07-4b45-a2b8-ba3f349d2211" />

### 🎬 Manage Movies
<img width="1876" height="907" alt="Manage Movies" src="https://github.com/user-attachments/assets/9d957a89-7d83-4caa-9e52-9779fa420e28" />

### 🎭 Manage Shows
<img width="1872" height="912" alt="Manage Shows" src="https://github.com/user-attachments/assets/d1df6228-c88f-4cea-84f0-21fda8f62b53" />

### 🍿 Manage Snacks
<img width="1882" height="910" alt="Manage Snacks" src="https://github.com/user-attachments/assets/9e5b536f-773b-42c2-93cb-609efdde2ef1" />

### 🚗 Manage Parking
<img width="1860" height="906" alt="Manage Parking" src="https://github.com/user-attachments/assets/b9870f48-121a-42ae-8e0b-f533ff16d053" />

### 📈 Revenue Analytics
<img width="1883" height="908" alt="Revenue Analytics" src="https://github.com/user-attachments/assets/d4338a3a-0d2b-41fb-b09b-bebd2c81e1f1" />

### 📊 Revenue Charts
<img width="1875" height="916" alt="Revenue Charts" src="https://github.com/user-attachments/assets/4195fa7b-c34c-4852-8645-a4b675d19645" />

### 🎟️ Booking Management
<img width="1878" height="912" alt="Booking Management" src="https://github.com/user-attachments/assets/63f58c8d-63c7-44a2-b30c-8ebbfef19e02" />

### 👥 User Management
<img width="1872" height="905" alt="User Management" src="https://github.com/user-attachments/assets/cd56bad1-cddd-448f-9a19-5e63d315573d" />

### 🔍 Ticket Scanner
<img width="1842" height="907" alt="Ticket Scanner" src="https://github.com/user-attachments/assets/73409498-a22b-4251-b325-e5bd42ade8e0" />

### ✅ Ticket Verification Result
<img width="1838" height="906" alt="Ticket Verification Result" src="https://github.com/user-attachments/assets/55f5116e-3948-4dcd-b783-f3c8e45f5fbc" />

### ⚙️ Admin Settings
<img width="1850" height="900" alt="Admin Settings" src="https://github.com/user-attachments/assets/a72fc89a-1691-46fb-b5be-47c12afaafeb" />

### 📋 System Overview
<img width="1855" height="898" alt="System Overview" src="https://github.com/user-attachments/assets/017d6270-50c7-435a-b270-ed355292848d" />









# 📸 Project Demo

## 👨‍💻 User Interface

<table>
<tr>
<td width="50%" align="center">

### 🏠 Home Page

<img src="https://github.com/user-attachments/assets/e6929446-8c54-44cb-9d8c-ca55b960d13e" width="100%"/>

</td>

<td width="50%" align="center">

### 🎬 Movies Listing

<img src="https://github.com/user-attachments/assets/8ac90a3f-96ca-4a27-b41e-128b61423267" width="100%"/>

</td>
</tr>

<tr><td colspan="2"><br><br></td></tr>

<tr>
<td align="center">

### 🎥 Movie Details

<img src="https://github.com/user-attachments/assets/42135c1e-f5f9-437a-940c-04e034dec93e" width="100%"/>

</td>

<td align="center">

### 🪑 Seat Selection

<img src="https://github.com/user-attachments/assets/8d8e0703-fdee-43b5-91aa-de05e56d1479" width="100%"/>

</td>
</tr>

<tr><td colspan="2"><br><br></td></tr>

<tr>
<td align="center">

### 🍿 Snacks & Add-ons

<img src="https://github.com/user-attachments/assets/203c9a6d-3a7a-47d6-a99f-f6e0febef3c1" width="100%"/>

</td>

<td align="center">

### 🚗 Parking Reservation

<img src="https://github.com/user-attachments/assets/8aad8831-f1a8-4b7b-89c0-aa5f30568a8e" width="100%"/>

</td>
</tr>

<tr><td colspan="2"><br><br></td></tr>

<tr>
<td align="center">

### 📅 My Bookings

<img src="https://github.com/user-attachments/assets/0e614067-3fc5-4f6d-abf6-2d267194f428" width="100%"/>

</td>

<td align="center">

### 🎟️ Ticket Verification

<img src="https://github.com/user-attachments/assets/e7b9ab14-fd0c-4e20-a20a-1c050d7a1904" width="100%"/>

</td>
</tr>

<tr><td colspan="2"><br><br></td></tr>

<tr>
<td colspan="2" align="center">

### 📱 QR Code Scanner

<img src="https://github.com/user-attachments/assets/f1a2beaa-9723-4471-879c-f90594ce37a6" width="45%"/>

</td>
</tr>

</table>

---

# 🛠️ Admin Dashboard

<table>

<tr>
<td width="50%" align="center">

### 📊 Dashboard Overview

<img src="https://github.com/user-attachments/assets/a451a2d0-ce07-4b45-a2b8-ba3f349d2211" width="100%"/>

</td>

<td width="50%" align="center">

### 🎬 Manage Movies

<img src="https://github.com/user-attachments/assets/9d957a89-7d83-4caa-9e52-9779fa420e28" width="100%"/>

</td>
</tr>

<tr><td colspan="2"><br><br></td></tr>

<tr>
<td align="center">

### 🎭 Manage Shows

<img src="https://github.com/user-attachments/assets/d1df6228-c88f-4cea-84f0-21fda8f62b53" width="100%"/>

</td>

<td align="center">

### 🍿 Manage Snacks

<img src="https://github.com/user-attachments/assets/9e5b536f-773b-42c2-93cb-609efdde2ef1" width="100%"/>

</td>
</tr>

<tr><td colspan="2"><br><br></td></tr>

<tr>
<td align="center">

### 🚗 Manage Parking

<img src="https://github.com/user-attachments/assets/b9870f48-121a-42ae-8e0b-f533ff16d053" width="100%"/>

</td>

<td align="center">

### 📈 Revenue Analytics

<img src="https://github.com/user-attachments/assets/d4338a3a-0d2b-41fb-b09b-bebd2c81e1f1" width="100%"/>

</td>
</tr>

<tr><td colspan="2"><br><br></td></tr>

<tr>
<td align="center">

### 📊 Revenue Charts

<img src="https://github.com/user-attachments/assets/4195fa7b-c34c-4852-8645-a4b675d19645" width="100%"/>

</td>

<td align="center">

### 🎟️ Booking Management

<img src="https://github.com/user-attachments/assets/63f58c8d-63c7-44a2-b30c-8ebbfef19e02" width="100%"/>

</td>
</tr>

<tr><td colspan="2"><br><br></td></tr>

<tr>
<td align="center">

### 👥 User Management

<img src="https://github.com/user-attachments/assets/cd56bad1-cddd-448f-9a19-5e63d315573d" width="100%"/>

</td>

<td align="center">

### 🔍 Ticket Scanner

<img src="https://github.com/user-attachments/assets/73409498-a22b-4251-b325-e5bd42ade8e0" width="100%"/>

</td>
</tr>

<tr><td colspan="2"><br><br></td></tr>

<tr>
<td align="center">

### ✅ Ticket Verification Result

<img src="https://github.com/user-attachments/assets/55f5116e-3948-4dcd-b783-f3c8e45f5fbc" width="100%"/>

</td>

<td align="center">

### ⚙️ Admin Settings

<img src="https://github.com/user-attachments/assets/a72fc89a-1691-46fb-b5be-47c12afaafeb" width="100%"/>

</td>
</tr>

<tr><td colspan="2"><br><br></td></tr>

<tr>
<td colspan="2" align="center">

### 📋 System Overview

<img src="https://github.com/user-attachments/assets/017d6270-50c7-435a-b270-ed355292848d" width="55%"/>

</td>
</tr>

</table>


# 📸 Project Demo

The following screenshots showcase the key features and user experience of the Movie Booking System.

---

## 🏠 Home Page

<p align="center">
<img src="IMAGE_LINK" width="90%">
</p>

---

## 🎬 Browse Movies

<p align="center">
<img src="IMAGE_LINK" width="90%">
</p>

---

## 🎥 Movie Details

<p align="center">
<img src="IMAGE_LINK" width="90%">
</p>

---

## 🪑 Seat Selection

<p align="center">
<img src="IMAGE_LINK" width="90%">
</p>

---

## 🍿 Food & Beverage Ordering

<p align="center">
<img src="IMAGE_LINK" width="90%">
</p>

---

## 🚗 Parking Booking

<p align="center">
<img src="IMAGE_LINK" width="90%">
</p>

---

## 📋 Booking Summary

<p align="center">
<img src="IMAGE_LINK" width="90%">
</p>

---

## 💳 Payment

<p align="center">
<img src="IMAGE_LINK" width="90%">
</p>

---

## 🎟️ My Bookings

<p align="center">
<img src="IMAGE_LINK" width="90%">
</p>

---

## 📱 QR Ticket

<p align="center">
<img src="IMAGE_LINK" width="55%">
</p>

---

# 🛠️ Admin Dashboard

---

## 📊 Dashboard

<p align="center">
<img src="IMAGE_LINK" width="90%">
</p>

---

## 🎬 Movie Management

<p align="center">
<img src="IMAGE_LINK" width="90%">
</p>

---

## 🎭 Show Management

<p align="center">
<img src="IMAGE_LINK" width="90%">
</p>

---

## 🍿 Snack Management

<p align="center">
<img src="IMAGE_LINK" width="90%">
</p>

---

## 🚗 Parking Management

<p align="center">
<img src="IMAGE_LINK" width="90%">
</p>

---

## 📈 Revenue Analytics

<p align="center">
<img src="IMAGE_LINK" width="90%">
</p>

---

## 📊 Revenue Reports

<p align="center">
<img src="IMAGE_LINK" width="90%">
</p>

---

## 🎫 Ticket Verification

<p align="center">
<img src="IMAGE_LINK" width="90%">
</p>

---

## 📱 QR Code Scanner

<p align="center">
<img src="IMAGE_LINK" width="90%">
</p>

---

## 👤 User Management

<p align="center">
<img src="IMAGE_LINK" width="90%">
</p>

---

## ⚙️ System Settings

<p align="center">
<img src="IMAGE_LINK" width="90%">
</p>



# 📸 Project Demo

## 👨‍💻 User Interface

<table>

<tr>
<td width="50%" align="center">

### 🏠 Home Page

<img src="https://github.com/user-attachments/assets/e6929446-8c54-44cb-9d8c-ca55b960d13e" width="100%"/>

</td>

<td width="50%" align="center">

### 🎬 Movies Listing

<img src="https://github.com/user-attachments/assets/8ac90a3f-96ca-4a27-b41e-128b61423267" width="100%"/>

</td>
</tr>

<tr><td colspan="2"><br><br></td></tr>

<tr>
<td align="center">

### 🎥 Movie Details

<img src="https://github.com/user-attachments/assets/42135c1e-f5f9-437a-940c-04e034dec93e" width="100%"/>

</td>

<td align="center">

### 🎟️ Shows Listing

<img src="https://github.com/user-attachments/assets/8d8e0703-fdee-43b5-91aa-de05e56d1479" width="100%"/>

</td>
</tr>

<tr><td colspan="2"><br><br></td></tr>

<tr>
<td align="center">

### 🎫 Show Details

<img src="https://github.com/user-attachments/assets/203c9a6d-3a7a-47d6-a99f-f6e0febef3c1" width="100%"/>

</td>

<td align="center">

### 🪑 Seat Selection

<img src="https://github.com/user-attachments/assets/8aad8831-f1a8-4b7b-89c0-aa5f30568a8e" width="100%"/>

</td>
</tr>

<tr><td colspan="2"><br><br></td></tr>

<tr>
<td align="center">

### 🍿 Add Extras (Snacks & Parking)

<img src="https://github.com/user-attachments/assets/0e614067-3fc5-4f6d-abf6-2d267194f428" width="100%"/>

</td>

<td align="center">

### 🎟️ My Booking Ticket

<img src="https://github.com/user-attachments/assets/e7b9ab14-fd0c-4e20-a20a-1c050d7a1904" width="100%"/>

</td>
</tr>

<tr><td colspan="2"><br><br></td></tr>

<tr>
<td colspan="2" align="center">

### 📱 Ticket QR Code

<img src="https://github.com/user-attachments/assets/f1a2beaa-9723-4471-879c-f90594ce37a6" width="45%"/>

</td>
</tr>

</table>

---

# 🛠️ Admin Dashboard

<table>

<tr>
<td width="50%" align="center">

### 📊 Dashboard Overview

<img src="https://github.com/user-attachments/assets/a451a2d0-ce07-4b45-a2b8-ba3f349d2211" width="100%"/>

</td>

<td width="50%" align="center">

### 🎬 Manage Movies

<img src="https://github.com/user-attachments/assets/9d957a89-7d83-4caa-9e52-9779fa420e28" width="100%"/>

</td>
</tr>

<tr><td colspan="2"><br><br></td></tr>

<tr>
<td align="center">

### 🎭 Manage Shows

<img src="https://github.com/user-attachments/assets/d1df6228-c88f-4cea-84f0-21fda8f62b53" width="100%"/>

</td>

<td align="center">

### 🎬 Manage Show Schedule

<img src="https://github.com/user-attachments/assets/9e5b536f-773b-42c2-93cb-609efdde2ef1" width="100%"/>

</td>
</tr>

<tr><td colspan="2"><br><br></td></tr>

<tr>
<td align="center">

### 🚗 Manage Parking

<img src="https://github.com/user-attachments/assets/b9870f48-121a-42ae-8e0b-f533ff16d053" width="100%"/>

</td>

<td align="center">

### 🍿 Manage Snacks

<img src="https://github.com/user-attachments/assets/d4338a3a-0d2b-41fb-b09b-bebd2c81e1f1" width="100%"/>

</td>
</tr>

<tr><td colspan="2"><br><br></td></tr>

<tr>
<td align="center">

### 🚗 Parking Management

<img src="https://github.com/user-attachments/assets/4195fa7b-c34c-4852-8645-a4b675d19645" width="100%"/>

</td>

<td align="center">

### 🎟️ Booking Analytics

<img src="https://github.com/user-attachments/assets/63f58c8d-63c7-44a2-b30c-8ebbfef19e02" width="100%"/>

</td>
</tr>

<tr><td colspan="2"><br><br></td></tr>

<tr>
<td align="center">

### 💰 Theatre Revenue Report

<img src="https://github.com/user-attachments/assets/cd56bad1-cddd-448f-9a19-5e63d315573d" width="100%"/>

</td>

<td align="center">

### 📊 Revenue Analytics

<img src="https://github.com/user-attachments/assets/73409498-a22b-4251-b325-e5bd42ade8e0" width="100%"/>

</td>
</tr>

<tr><td colspan="2"><br><br></td></tr>

<tr>
<td align="center">

### 🎟️ Ticket Scanner

<img src="https://github.com/user-attachments/assets/55f5116e-3948-4dcd-b783-f3c8e45f5fbc" width="100%"/>

</td>

<td align="center">

### 📊 System Statistics

<img src="https://github.com/user-attachments/assets/a72fc89a-1691-46fb-b5be-47c12afaafeb" width="100%"/>

</td>
</tr>

<tr><td colspan="2"><br><br></td></tr>

<tr>
<td colspan="2" align="center">

### ✅ Ticket Verification Result

<img src="https://github.com/user-attachments/assets/017d6270-50c7-435a-b270-ed355292848d" width="55%"/>

</td>
</tr>

</table>






