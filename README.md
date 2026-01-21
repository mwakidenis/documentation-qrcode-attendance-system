## QR SCAN ATTENDANCE SYSTEM

## 📘 Abstract
QR Attendance is a mobile application developed to streamline classroom attendance marking using **QR codes** and **GPS validation**. The system allows lecturers to generate secure, time-limited QR codes tied to a specific location, which students scan using their mobile devices to mark attendance instantly.

The system supports **faculty** and **students**, providing real-time attendance tracking, offline support, secure authentication using Firebase, and detailed attendance analytics.

---

## 1.0 Introduction
The QR Attendance System modernizes attendance tracking by enabling students to scan session-specific QR codes using a mobile app. It improves efficiency, accuracy, and scalability while minimizing fraud.

---

## 1.1 Background
Traditional attendance methods are time-consuming, error-prone, and susceptible to manipulation. As class sizes grow, these problems become more severe.

By leveraging **QR code technology**, **Firebase**, and **GPS verification**, this system provides a secure and automated alternative for Meru University.

---

## 1.2 Problem Statement
Manual attendance systems:
- Waste lecture time
- Are prone to proxy attendance
- Lack real-time accuracy
- Risk data loss

The QR Attendance System addresses these issues using automation and location validation.

---

## 1.3 Methodology

### 1.3.1 Frontend Development
- Android Studio (Meerkat 2024.3.1)
- Java & XML
- Firebase Authentication
- Firebase Realtime Database

### 1.3.2 Backend Development
- Firebase Authentication
- Firebase Realtime Database
- Firebase Cloud Storage
- Google Maps API (GPS validation)

---

## 1.4 Implementation
The system was implemented as a pilot project at Meru University on Android devices. Lecturers generate QR codes per session, while students scan them within a defined location and time.

---

## 1.4.1 Challenges and Limitations
- Device compatibility
- GPS accuracy indoors
- Email-only authentication
- QR code projection via web

---

## 1.4.2 Overcoming the Challenges
- Responsive UI testing
- GPS offset zones
- Custom authentication proposals
- Secure web-based QR projection

---

## 1.5 Results and Discussion

### 1.5.1 Results
The system successfully:
- Reduced attendance marking time
- Prevented proxy attendance
- Enabled real-time updates
- Provided offline functionality

### 1.5.2 Discussion
While effective, GPS accuracy and older device performance remain areas for improvement.

---

## 📸 Application Screenshots

### App Icon
![App Icon](images/app-icon.png)

### Home Page
![Home Page](images/home-page.png)

### Faculty Login
![Faculty Login](images/faculty-login.png)

### Scan QR Page
![Scan QR](images/scan-qr.png)

### Attendance Success
![Success](images/success-attendance.png)

---

## 1.6 Conclusions and Recommendations

### Conclusions
The QR Attendance System significantly improves attendance accuracy and efficiency through QR scanning and real-time synchronization.

### Recommendations
- Improve GPS with BLE/Wi-Fi
- Develop iOS version
- Optimize for low-end devices
- Enhance offline caching
- Continuous user feedback

---

## 📚 References
1. Firebase Documentation – https://firebase.google.com/docs  
2. Android Developers Guide – https://developer.android.com  
3. ZXing QR Library – https://github.com/zxing/zxing  
4. CameraX Library – https://developer.android.com/training/camerax  
