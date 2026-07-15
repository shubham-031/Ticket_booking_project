# 🎬 CineBook - Full Stack Movie Booking & Theatre Management System

<p align="center">

![React](https://img.shields.io/badge/React-19-61DAFB?logo=react)
![Node.js](https://img.shields.io/badge/Node.js-Express-339933?logo=node.js)
![MongoDB](https://img.shields.io/badge/MongoDB-Database-47A248?logo=mongodb)
![JWT](https://img.shields.io/badge/Auth-JWT-orange)
![License](https://img.shields.io/badge/License-MIT-blue)

</p>

A **production-ready MERN Stack Movie Booking & Theatre Management Platform** that delivers a complete digital cinema experience for both customers and theatre administrators.

The platform enables users to browse movies, reserve seats, purchase snacks, book parking, download QR-based tickets, and manage bookings, while providing administrators with a centralized dashboard for movie management, theatre operations, ticket verification, and revenue analytics.

---

# ✨ Features

## 👨‍💻 Customer Features

✅ Authentication & Authorization

- Secure User Login & Registration
- JWT Authentication
- Protected Routes

---

✅ Movie Discovery

- Browse Latest Movies
- Search Movies
- Genre Filtering
- Movie Details
- Responsive UI

---

✅ Smart Booking

- Show Selection
- Interactive Seat Selection
- Live Seat Availability
- Automatic Price Calculation

---

✅ Add-ons

- Snack Booking
- Parking Reservation
- Multiple Theatre Support

---

✅ Ticket Management

- QR Code Ticket Generation
- Download Ticket as PDF
- My Bookings
- Booking History
- Ticket Verification

---

## 🛠️ Admin Features

### Dashboard

- Overall Statistics
- Total Revenue
- Active Shows
- Ticket Analytics

### Movie Management

- Add Movie
- Update Movie
- Delete Movie
- Manage Posters

### Show Management

- Manage Shows
- Manage Show Slots
- Theatre Assignment
- Ticket Pricing

### Snack Management

- Add Snacks
- Edit Snacks
- Theatre-wise Snacks

### Parking Management

- Parking Slot Management
- Theatre-wise Parking Pricing

### Analytics

- Revenue Analytics
- Theatre Revenue Report
- Booking Analytics
- Ticket Statistics

### Ticket Verification

- QR Ticket Scanner
- Verify Ticket
- Prevent Duplicate Entry

---

# 🚀 Highlights

- 🎬 Netflix Inspired Dark UI
- ⚡ Smooth Animations using Framer Motion
- 🎟 QR Code Based Digital Tickets
- 📄 PDF Ticket Download
- 🪑 Interactive Seat Selection
- 🍿 Snack & Parking Booking
- 📊 Real-time Revenue Analytics
- 🔐 JWT Authentication
- 📱 Fully Responsive Design
- ⚙️ Complete Admin Dashboard

---

# 🏗️ Tech Stack

## Frontend

- React.js
- React Router DOM
- Tailwind CSS
- Framer Motion
- Axios
- QRCode.react
- jsPDF
- html2canvas

---

## Backend

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- REST APIs

---

## Tools

- Git
- GitHub
- VS Code
- Postman

---

# 📁 Project Structure

```text
Movie-Booking-System-MERN

├── client
│
├── server
│
├── README.md
│
└── package.json
```

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/yourusername/CineBook.git
```

```bash
cd CineBook
```

---

## Backend

```bash
cd server

npm install
```

Create `.env`

```env
PORT=5000

MONGO_URI=your_mongodb_uri

JWT_SECRET=your_secret_key
```

Run

```bash
npm start
```

---

## Frontend

```bash
cd client

npm install

npm start
```

---

# 🔐 Admin Login

For demonstration purposes,

```
Password

123456
```

---

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

### ✏️ Manage & Edit Show Slots

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

### 🎟️ Movie Revenue Chart

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






