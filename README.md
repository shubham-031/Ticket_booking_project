# 🎬 CineBook - Movie Ticket Booking Management System

### *A Full Stack MERN-Based Movie Booking & Theatre Management Platform*

---

## 🚀 Live Demo

🌐 **Project Demo:**  
👉 **https://movie-booking-system-mern-fawn.vercel.app/**

---
# 🎯 Problem Statement

Traditional movie ticket booking systems mainly focus on reserving seats and generating tickets. However, real-world theatre operations involve much more than ticket booking.

Managing movie schedules, theatre-wise show slots, snack ordering, parking reservations, ticket verification, booking analytics, and revenue monitoring are often handled using multiple disconnected systems or manual processes. This increases operational complexity, consumes valuable time, and reduces overall efficiency.

There is a need for a unified platform that not only provides customers with a smooth digital booking experience but also enables theatre administrators to manage daily operations from a single centralized system.

**CineBook** addresses this challenge by integrating movie booking, theatre management, QR-based ticket verification, snack ordering, parking reservation, analytics, and administrative controls into one production-ready application.

---

# 💡 Solution

CineBook is designed as a complete theatre management ecosystem built using the MERN Stack.

The platform enables customers to discover movies, book tickets, select seats, reserve snacks and parking, generate QR-based digital tickets, and download booking confirmations. On the administrative side, it provides a centralized dashboard for managing movies, shows, theatres, snacks, parking, bookings, ticket verification, and business analytics.

The application eliminates manual theatre operations while delivering a modern, secure, and user-friendly booking experience.

---

# 🎯 Project Objectives

- Develop a complete digital movie booking platform.
- Simplify theatre management using a centralized admin dashboard.
- Eliminate manual ticket verification using QR codes.
- Improve customer convenience through online snack and parking reservations.
- Provide theatre owners with real-time revenue and booking analytics.
- Build a scalable full-stack application following industry-standard MERN architecture.

---

# 👨‍💻 Customer Features

The customer module is designed to provide a smooth, secure, and user-friendly movie booking experience. From discovering movies to downloading QR-based tickets, every step is optimized to minimize booking time while ensuring convenience.

---

## 🔐 User Authentication

The application provides a secure authentication system using **JWT (JSON Web Token)**. Users can create an account, log in securely, and access protected features such as ticket booking, booking history, and ticket downloads.

### Key Features

| Feature | Description |
|---------|-------------|
| 📝 User Registration | Create a new account with secure credentials. |
| 🔑 Secure Login | Authenticate users using JWT tokens. |
| 🛡 Protected Routes | Restrict booking features to authenticated users only. |
| 🚪 Logout | Securely terminate user sessions. |

---

## 🎬 Movie Discovery

Users can easily discover movies through a clean and responsive interface. Movies can be searched by title or filtered based on genres, making it easier to find preferred content.

### Key Features

| Feature | Description |
|---------|-------------|
| 🎥 Browse Movies | View all available movies currently running. |
| 🔍 Search Movies | Search movies instantly by title. |
| 🎭 Genre Filtering | Filter movies based on selected genres. |
| 📄 Movie Details | View synopsis, duration, cast, language, genre, ratings, and release information. |
| 📱 Responsive Design | Optimized experience across desktop, tablet, and mobile devices. |

---

## 🎟 Show Selection

After selecting a movie, users can view all available theatres along with show timings and ticket prices.

The system supports multiple theatres and multiple show slots for each movie, allowing users to select the most convenient schedule.

### Key Features

| Feature | Description |
|---------|-------------|
| 🏢 Theatre Selection | Choose from available theatres. |
| 🕒 Show Timings | Display multiple show slots. |
| 📅 Date Selection | Select preferred booking date. |
| 💰 Ticket Pricing | Display ticket price before booking. |

---

## 🪑 Interactive Seat Selection

The application provides an interactive graphical seat layout where users can select available seats.

Seats are categorized into different classes such as **Balcony**, **Gold**, and **Silver**, each with different pricing. The total ticket amount updates automatically as seats are selected.

### Key Features

| Feature | Description |
|---------|-------------|
| 🪑 Visual Seat Layout | Interactive theatre seat map. |
| ✅ Live Seat Availability | Prevents selection of already booked seats. |
| 💰 Category-wise Pricing | Balcony, Gold, and Silver seat pricing. |
| 🎟 Multiple Seat Booking | Book one or more seats in a single transaction. |
| ⚡ Automatic Price Calculation | Updates total amount instantly. |

---

## 🍿 Snack Booking

Customers can pre-order snacks while booking movie tickets, eliminating the need to wait in queues during intervals.

Each theatre maintains its own snack menu with customizable prices.

### Key Features

| Feature | Description |
|---------|-------------|
| 🍔 Theatre-wise Snack Menu | Different snack menus for different theatres. |
| ➕ Quantity Selection | Select multiple snack quantities. |
| 💵 Dynamic Pricing | Automatically calculates snack charges. |
| 🧾 Booking Integration | Snacks are added to the final booking summary. |

---

## 🚗 Parking Reservation

Users can reserve parking while booking tickets.

Separate pricing can be configured for bike and car parking based on the selected theatre.

### Key Features

| Feature | Description |
|---------|-------------|
| 🏍 Bike Parking | Reserve two-wheeler parking. |
| 🚘 Car Parking | Reserve four-wheeler parking. |
| 🏢 Theatre-wise Pricing | Parking charges vary by theatre. |
| 💰 Automatic Billing | Parking charges are included in the total amount. |

---

## 📋 Booking Summary

Before confirming the booking, users receive a detailed summary of their entire order.

This helps users verify all booking details before making the final confirmation.

### Summary Includes

| Information |
|-------------|
| 🎬 Movie Details |
| 🏢 Theatre Name |
| 📅 Show Date & Time |
| 🪑 Selected Seats |
| 🍿 Snacks |
| 🚗 Parking |
| 💰 Total Amount |

---

## 📱 QR Code Ticket Generation

Once the booking is successfully completed, the system generates a unique QR Code for every ticket.

This QR code is later used by theatre staff to verify the authenticity of the booking during entry.

### Key Features

| Feature | Description |
|---------|-------------|
| 📱 Unique QR Code | QR generated for every booking. |
| 🎟 Booking ID | Unique booking identifier. |
| 🔐 Secure Verification | Prevents fake or duplicate tickets. |
| 📚 Booking History | View all previous bookings. |

---

## 📄 PDF Ticket Download

Customers can download their booking as a professionally formatted PDF ticket.

The downloaded ticket contains all booking information and can also be used without internet connectivity.

### Ticket Includes

| Information |
|-------------|
| 🎬 Movie Details |
| 🏢 Theatre |
| 🪑 Seats |
| 🍿 Snacks |
| 🚗 Parking |
| 📅 Show Date & Time |
| 📱 QR Code |
| 🎟 Booking ID |

---

# 🛠️ Admin Features

The Admin Module serves as the central control system for managing the entire theatre ecosystem. It enables administrators to manage movies, theatres, show schedules, snacks, parking, bookings, ticket verification, and revenue analytics from a single dashboard.

The dashboard is designed to reduce manual operations and provide complete visibility into theatre performance through real-time insights.

---

## 📊 Admin Dashboard

The Admin Dashboard provides a centralized overview of the entire system by displaying important business metrics and operational statistics.

It allows administrators to quickly monitor theatre performance without navigating through multiple modules.

### Dashboard Overview

| Feature | Description |
|---------|-------------|
| 📈 Revenue Summary | Displays overall revenue generated from ticket bookings. |
| 🎟 Booking Statistics | Shows total bookings and daily booking trends. |
| 🎬 Active Movies | Displays currently running movies. |
| 🎭 Active Shows | View all scheduled shows across theatres. |
| 📊 Business Insights | Quick overview of system performance. |

---

## 🎬 Movie Management

Administrators can efficiently manage the complete movie catalog from a single interface.

The system supports creating new movies, updating existing information, changing posters, and removing outdated movies.

### Key Features

| Feature | Description |
|---------|-------------|
| ➕ Add Movie | Add new movies with complete information. |
| ✏ Edit Movie | Update movie details such as title, description, genre, language, duration, cast, and poster. |
| ❌ Delete Movie | Remove movies that are no longer available. |
| 🖼 Poster Management | Upload and update movie posters. |
| 🎭 Genre Management | Organize movies based on categories. |

---

## 🎭 Show Management

The Show Management module allows administrators to schedule movie shows for different theatres.

Multiple show slots can be created for the same movie with separate ticket pricing and timings.

### Key Features

| Feature | Description |
|---------|-------------|
| ➕ Create Shows | Schedule new movie shows. |
| 🕒 Manage Show Slots | Configure multiple show timings. |
| 🏢 Theatre Assignment | Assign shows to specific theatres. |
| 💰 Ticket Pricing | Configure ticket prices for each show. |
| ✏ Edit Shows | Modify existing show schedules. |
| ❌ Delete Shows | Remove cancelled or expired shows. |

---

## 🍿 Snack Management

Each theatre can maintain its own snack menu.

Administrators can add, edit, or remove snacks while configuring different prices for individual theatres.

### Key Features

| Feature | Description |
|---------|-------------|
| ➕ Add Snacks | Add new snack items. |
| ✏ Update Snacks | Modify snack details and pricing. |
| ❌ Delete Snacks | Remove unavailable snacks. |
| 🏢 Theatre-wise Menu | Configure different menus for different theatres. |

---

## 🚗 Parking Management

Parking facilities can be configured separately for every theatre.

Administrators can manage both bike and car parking charges.

### Key Features

| Feature | Description |
|---------|-------------|
| 🏍 Bike Parking | Configure bike parking availability. |
| 🚘 Car Parking | Configure car parking availability. |
| 💰 Parking Charges | Manage parking prices. |
| 🏢 Theatre-wise Configuration | Different pricing for different theatres. |

---

## 🎟 Booking Management

The Booking Management module provides administrators with complete visibility into all customer bookings.

Administrators can monitor booking activity, ticket status, and booking details whenever required.

### Key Features

| Feature | Description |
|---------|-------------|
| 📋 Booking Records | View all customer bookings. |
| 🔍 Booking Details | Access complete booking information. |
| 🎟 Ticket Status | Track booking and ticket status. |
| 📊 Booking Insights | Analyze booking trends. |

---

## 📱 Ticket Verification

Every booking generates a unique QR Code which is used during theatre entry.

The administrator can scan or verify tickets using the built-in verification system. Once verified, the ticket status is updated automatically to prevent duplicate entry.

### Verification Flow

```
Ticket Booked
       │
       ▼
QR Code Generated
       │
       ▼
Ticket Scanned
       │
       ▼
Ticket Verified
       │
       ▼
Status Updated
(VALID → USED)
```

### Key Features

| Feature | Description |
|---------|-------------|
| 📱 QR Scanner | Scan customer tickets using QR codes. |
| ✅ Ticket Validation | Verify ticket authenticity instantly. |
| 🚫 Duplicate Entry Prevention | Prevent multiple entries using the same ticket. |
| 🔄 Status Update | Automatically updates ticket status after verification. |
| 📋 Booking Lookup | Search bookings using Booking ID. |

---

## 📊 Revenue Analytics

The Revenue Analytics module provides graphical insights into theatre performance.

Administrators can monitor revenue trends, booking statistics, and overall business growth through interactive dashboards.

### Reports Include

| Report | Description |
|---------|-------------|
| 💰 Total Revenue | Overall revenue generated. |
| 🎟 Ticket Revenue | Revenue earned through ticket sales. |
| 🍿 Snack Revenue | Revenue generated from snacks. |
| 🚗 Parking Revenue | Parking income analysis. |
| 📊 Booking Analytics | Daily, weekly, and monthly booking statistics. |
| 📈 Revenue Charts | Interactive graphical reports. |

---

## 📊 System Statistics

The dashboard also displays important operational statistics that help administrators understand overall system performance.

| Statistic | Description |
|-----------|-------------|
| 👥 Registered Users | Total number of users registered on the platform. |
| 🎬 Movies | Total movies available in the system. |
| 🎭 Active Shows | Currently running shows. |
| 🎟 Tickets Booked | Total successful bookings. |
| 💰 Revenue | Overall business revenue. |
| 🍿 Snack Orders | Total snack orders placed. |
| 🚗 Parking Reservations | Total parking bookings. |

---

# 🔒 Security Features

The platform follows secure authentication and authorization mechanisms to protect sensitive data and administrative functionalities.

| Security Feature | Description |
|------------------|-------------|
| 🔐 JWT Authentication | Secure user authentication using JSON Web Tokens. |
| 🛡 Protected Routes | Restricts unauthorized access to protected pages. |
| 👤 Role-Based Access | Different access levels for users and administrators. |
| 🔑 Admin Authentication | Secure admin login for dashboard access. |
| 📱 Secure QR Verification | Prevents fake or duplicate ticket usage. |

---

# 🏗️ Technology Stack

The project is built using the **MERN Stack Architecture**, following a modular and scalable design pattern. Each technology is selected to provide better performance, maintainability, and developer productivity.

| Category | Technologies Used |
|----------|-------------------|
| 🎨 Frontend | React.js, React Router DOM, Tailwind CSS, Framer Motion |
| ⚙️ Backend | Node.js, Express.js |
| 🗄️ Database | MongoDB Atlas, Mongoose ODM |
| 🔐 Authentication | JWT (JSON Web Token), Role-Based Authentication |
| 📡 API Communication | REST APIs, Axios |
| 📱 QR Code | qrcode.react |
| 📄 PDF Generation | jsPDF, html2canvas |
| 🎨 UI Design | Tailwind CSS, Responsive Design |
| 🛠 Development Tools | VS Code, Git, GitHub, Postman |
| ☁️ Deployment Ready | Environment Variables (.env), Modular Architecture |

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






# 🏛️ Project Architecture

The application follows a **three-tier MERN architecture** where the frontend communicates with backend APIs, and the backend interacts with the MongoDB database.

```text
               ┌─────────────────────────┐
               │      React Frontend     │
               │  (User & Admin Panels)  │
               └────────────┬────────────┘
                            │
                     REST APIs (Axios)
                            │
               ┌────────────▼────────────┐
               │    Express + Node.js    │
               │ Business Logic & APIs   │
               └────────────┬────────────┘
                            │
                     Mongoose ODM
                            │
               ┌────────────▼────────────┐
               │       MongoDB Atlas      │
               │     Application Data     │
               └─────────────────────────┘
```

---

# 📂 Project Structure

```text
Movie-Booking-System-MERN
│
├── client
│   ├── public
│   ├── src
│   │   ├── components
│   │   ├── pages
│   │   ├── context
│   │   ├── hooks
│   │   ├── services
│   │   ├── utils
│   │   ├── assets
│   │   └── App.jsx
│   │
│   └── package.json
│
├── server
│   ├── controllers
│   ├── middleware
│   ├── models
│   ├── routes
│   ├── config
│   ├── utils
│   ├── uploads
│   ├── server.js
│   └── package.json
│
├── README.md
└── .gitignore
```

---

# ⚙️ Installation Guide

## 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/CineBook.git

cd CineBook
```

---

## 2️⃣ Install Backend

```bash
cd server

npm install
```

Create a `.env` file inside the **server** directory.

```env
PORT=5000

MONGO_URI=your_mongodb_connection_string

JWT_SECRET=your_secret_key
```

Start Backend

```bash
npm start
```

---

## 3️⃣ Install Frontend

```bash
cd client

npm install
```

Create a `.env` file

```env
REACT_APP_API_URL=http://localhost:5000
```

Start Frontend

```bash
npm start
```

---

# 🔐 Admin Access

For demonstration purposes, the application provides a predefined administrator access.

| Username | Value |
|-----------|-------|
| Admin Password | **123456** |

After successful authentication, administrators gain access to:

- Dashboard
- Movie Management
- Show Management
- Snack Management
- Parking Management
- Revenue Analytics
- Booking Management
- Ticket Verification

---

# 👨‍💻 Author

## Shubham Jadhav

**Full Stack Developer**



</div>



