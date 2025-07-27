# Gas-Agency-System

:

🏭 Gas Agency System
A web-based Gas Agency System developed using HTML, CSS, JavaScript, and Firebase. This application allows users to register, book gas cylinders, and track their booking status, while admins can manage bookings and customer records in real-time.

🔍 Project Overview
The Gas Agency System simplifies the manual process of gas cylinder booking and management. It provides an easy-to-use interface for customers and a backend dashboard for agency staff powered by Firebase for real-time data storage and authentication.

✨ Features
👤 User Features
User registration and login using Firebase Authentication

Book gas cylinder online

View booking history and current booking status

Mobile-friendly responsive design

🛠 Admin Features
Admin login panel

View and manage customer bookings

Update booking status (Pending, Confirmed, Delivered)

Real-time updates with Firebase Realtime Database

🧰 Tech Stack
Technology	Purpose
HTML & CSS	Structure and styling
JavaScript	Functionality and interactivity
Firebase Auth	User authentication (login/signup)
Firebase DB	Realtime database for bookings

📁 File Structure
perl
Copy code
gas-agency-system/
├── index.html            # Home page
├── login.html            # Login page for users/admin
├── register.html         # Registration page
├── dashboard.html        # User dashboard
├── admin.html            # Admin dashboard
├── style.css             # All CSS styles
└── script.js             # Main JavaScript logic
└── firebase-config.js    # Firebase configuration and setup
🚀 How to Run the Project
Clone the repository or download the code.
git clone https://github.com/Yuvarani2005yuva/Gas-Agency-System
Set up Firebase:

Go to Firebase Console

Create a new project

Enable Authentication and Realtime Database

Copy your Firebase config and paste it into firebase-config.js

Open index.html in your browser to get started.

🔐 Firebase Setup
Make sure to:

Enable Email/Password Authentication

Set Realtime Database rules (for testing):
{
  "rules": {
    ".read": true,
    ".write": true
  }
}
⚠ For production, make your rules more secure!

🎯 Future Enhancements
SMS or Email notification integration

Payment gateway for cylinder booking

Admin analytics dashboard (daily bookings, delivery status)

Search and filter options for admin

🙏 Acknowledgments
Firebase for providing free backend services

Inspired by real-world gas booking systems

📄 License
This project is open-source and available for learning and personal use.
