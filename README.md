🔐 Login with OTP (Frontend Demo)

A simple and responsive Login with OTP verification system built using HTML, CSS, and JavaScript.
This project demonstrates how OTP-based login works on the frontend using a randomly generated OTP (demo purpose only).

📌 Features

User login using:

Full Name

Email ID

Contact Number

Random 6-digit OTP generation

OTP verification screen

OTP sent success notification

Login success popup with user name

Clean UI with gradient background

Fully responsive design

No backend required (Frontend demo)

🛠️ Technologies Used

HTML5 – Structure

CSS3 – Styling & animations

JavaScript (Vanilla JS) – OTP generation & validation

📂 Project Structure
Login-with-OTP/
│
├── index.html
└── README.md

🚀 How It Works

User enters:

Full Name

Email ID

10-digit Contact Number

Click Send OTP

A 6-digit OTP is generated using JavaScript

OTP is shown on screen (demo purpose)

User enters OTP and clicks Verify & Login

If OTP is correct → Login successful popup appears

If OTP is incorrect → Error message is shown

🔢 OTP Logic (Demo)

OTP is generated using:

Math.floor(100000 + Math.random() * 900000)


OTP is displayed on screen for learning/demo

No real SMS or email service is used

📷 Screens Included

Login Form

OTP Verification Screen

OTP Sent Notification

Login Success Popup

⚠️ Important Note

⚠️ This project is for learning and demonstration only.
It does not include:

Backend authentication

Real SMS/Email OTP service

Database storage

For real-world use, integrate:

Backend (Node.js / PHP / Python)

SMS APIs (Twilio, Fast2SMS, etc.)

Secure OTP handling

✅ Use Cases

College mini project

Frontend practice

JavaScript learning

UI/UX demonstration

GitHub portfolio project

📄 License

This project is free to use for educational purposes.

👩‍💻 Author

Anushka Jadhav
Frontend Practice Project
