# 🏥 Hospital Management System - Backend

This is the backend service for the Hospital Management System project.  
It handles authentication, patient management, doctor scheduling, appointments, billing, and more.

---

## 🚀 How to Run

1. Clone the repository  
   ```bash
      git clone https://github.com/BhanuVignesh2300033284/hospital-backend.git
2. Navigate to the project directory
   ```bash
   cd hospital-backend
3. Run the backend using Docker
   ```bash
   docker compose up -d --build

4. Start the Spring Boot application (using your IDE or command line)
   The backend will run on:
   http://localhost:8081
   
🧪 Output Verification
 To verify the backend API is working correctly, open this link in your browser or API tool:

http://localhost:8081/auth/signup?username=testuser&email=testuser@gmail.com&password=admin123

⚙️ Notes
Make sure your database (MySQL/PostgreSQL) is running before starting the application.

Default backend port → 8081

Frontend runs on → http://localhost:5173
