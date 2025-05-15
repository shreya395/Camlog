CamLog - Attendance Tracking System
CamLog is an industry-oriented, full-stack web application designed to digitize and secure the classroom attendance process using facial recognition technology. The system eliminates manual roll calls by enabling real-time biometric authentication through a responsive and user-friendly interface.

🚀 Features
🎯 Facial Recognition-Based Attendance
🧑‍💼 Role-Based Access (Admin, Faculty, Student)
📊 Real-Time Attendance Reports
📸 Integrated Webcam Access for Face Scanning
📅 Attendance Logs
🔐 Secure Authentication System
📸 Tech Stack
🔧 Backend Technologies
Django: High-level Python web framework enabling rapid, secure, and scalable development. Follows MTV (Model-Template-View) architecture.
Django REST Framework (if used): Simplifies the creation of robust APIs for frontend-backend interaction.
SQLite / PostgreSQL: Relational database for storing user profiles, facial data, and attendance records.
OpenCV & Face Recognition (Python): For facial detection, recognition, and image preprocessing.
🎨 Frontend Technologies
HTML5, CSS3, JavaScript
Bootstrap: For responsive UI components.
AJAX / Fetch API: For smooth frontend-backend data flow.
(Optional: React or Vue.js if used)
--Installation

Clone the Repository git clone cd camlog

Create Virtual Environment & Activate python -m venv venv source venv/bin/activate # On Windows: venv\Scripts\activate

install Dependencies pip install -r requirements.txt

Run Migrations python manage.py migrate

Start Development Server python manage.py runserver