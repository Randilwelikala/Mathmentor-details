# MathMentor: LMS for Mathematics Tuition Classes

---

## Project Overview

MathMentor is a full-stack Learning Management System (LMS) tailored specifically for managing private mathematics tuition classes for grades 6 to 11. This platform empowers a single admin (the tutor) to manage students, track attendance via QR codes, handle fee payments, record academic progress, and visualize performance data — all in one intuitive dashboard.

This project demonstrates my skills in modern web development, authentication flows, real-time attendance systems, data visualization, and deployment using industry-standard tools and best practices.

---

## Features

### Admin Capabilities
- View and manage pending student signup requests (approve/reject).
- Generate unique student IDs and QR codes for attendance tracking.
- Add, edit, and delete student records.
- Scan QR codes to mark student attendance in real-time.
- Input monthly and term test marks for students.
- Manage monthly fee payments and track payment history.
- Visualize student attendance, marks, and fees through interactive charts.
- Receive notifications about low attendance or unpaid fees.

### Student Capabilities
- Secure sign-up (pending admin approval).
- Login to view personal profile, attendance, fee history, and academic performance.
- Visual analysis of monthly and term test marks.
- Ability to reset password securely via Firebase Authentication.
  
---

## Technologies Used

| Layer          | Technology               | Purpose                                        |
|----------------|--------------------------|------------------------------------------------|
| Frontend       | React.js + Tailwind CSS  | Component-based UI and responsive styling      |
| Data Visualization | Chart.js / Recharts   | Interactive charts for analytics                |
| Backend        | Node.js + Express.js     | REST API and server-side logic                   |
| Database       | MongoDB Atlas            | Cloud-hosted NoSQL data storage                  |
| Authentication | Firebase Authentication  | Secure email/password login and password reset |
| QR Code        | qrcode + html5-qrcode    | Generating and scanning QR codes for attendance |
| Deployment     | Vercel (frontend), Railway (backend) | Cloud hosting with CI/CD integration  |
| Version Control| Git + GitHub             | Source code management and collaboration         |

---

## Architecture Overview

- **Frontend:** React SPA consuming RESTful APIs, featuring protected routes and role-based access.
- **Backend:** Express API server handling business logic, authentication, and data persistence.
- **Database:** MongoDB Atlas collections for students, attendance, marks, fees, and signup requests.
- **Authentication:** Firebase manages secure user sign-up, login, and password reset flows.
- **QR Attendance:** QR code generation for each student and live QR code scanning for attendance marking.
- **Deployment:** Hosted on Vercel (frontend) and Railway (backend) with automated deployments on GitHub pushes.

---

## Screenshots

### 1. Admin 
![Admin Login](./screenshots/admin-login.png)
![Admin Dashboard](./screenshots/admin-dashboard.png)
![Admin Signup Request Page](./screenshots/admin-signup-request.png)
![Admin Approved Students Page](./screenshots/admin-approved-student.png)
![Admin Student Profile Full Page](./screenshots/admin-student-profile-full.png)
![Admin Student Profile Student Details Section](./screenshots/admin-student-profile-details.png)
![Admin Student Profile Mark Overview Section](./screenshots/admin-student-profile-marks.png)

![Admin Student Profile Add Mark,Fees,Attendance Section](./screenshots/admin-student-profile-add.png)
![Admin Student Profile Attendance and fees Overview Section](./screenshots/admin-student-profile-fees-marks.png)
![Admin All Student's Marks page](./screenshots/admin-all-student-marks.png)
![Admin All Student's Attendance page](./screenshots/admin-all-student-attendance.png)
![Admin All Student's Fees page](./screenshots/admin-all-student-fees.png)
![Admin All Student's ID Card page](./screenshots/admin-all-student-id-cards.png)
![Admin QR Scan page](./screenshots/admin-qr-scan-page.png)

### 2. Student 
![Student Signup Requests Page ](./screenshots/signup-requests.png)
![Student Login Page ](./screenshots/login-page.png)
![Student Profile View Full Page ](./screenshots/student-profile-full.png)
![Student profile View Details Section ](./screenshots/student-details-section.png)
![Student profile View Marks Overview Section](./screenshots/student-marks-section.png)
![Student profile View Attendance Section](./screenshots/student-attendance-section.png)
![Student profile View Fees Section](./screenshots/strudent-fees-section.png)


### 3. Student Performance Charts  
![Performance Charts Marks](./screenshots/performance-charts-marks.png)
![Performance Charts Attendance](./screenshots/performance-charts-attendance.png)
![Performance Charts Fees](./screenshots/performance-charts-fees.png)

---

## 🚀 Future Plans

- **Mobile App:** Develop a React Native app for student access on-the-go.
- **Notifications:** Real-time email/SMS reminders for fee dues and attendance alerts.
- **Reports Export:** Enable PDF and Excel report downloads for admin and students.
- **Role Expansion:** Add teacher role for class assistants with limited permissions.
- **Analytics Enhancements:** Advanced filtering, predictive analytics on student performance.
- **Localization:** Support for multiple languages based on user preferences.

---

## Accessing the Source Code

The full source code of the MathMentor LMS is currently **private** to protect sensitive data and ensure integrity during ongoing development.

**If you are a recruiter, employer, or collaborator interested in reviewing the codebase, please reach out to me at:**

**[your-email@example.com]**  
**LinkedIn:** [https://www.linkedin.com/in/your-profile](https://www.linkedin.com/in/your-profile)  
**Phone:** +94 XX XXXXXXX

_I am happy to provide private access or share the code upon request._

---

## About Me

I am an undergraduate Software Engineering student passionate about building full-stack applications with real-world impact. This project, MathMentor, reflects my skills in:

- Modern frontend and backend development
- Secure authentication and role-based access control
- Real-time features like QR code attendance
- Data visualization and analytics dashboards
- Cloud deployment and continuous integration

---

## Connect with Me
- GitHub: https://github.com/yourusername
- LinkedIn: https://www.linkedin.com/in/your-profile
- Email: your-email@example.com

## License
This project is for personal and portfolio use. Please contact me for collaboration or commercial usage.
