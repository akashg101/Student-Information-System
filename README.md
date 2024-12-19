# Student Information System (Admin Access Only)

## Description
The **Student Information System (SIS)** is a secure web-based application designed exclusively for administrators to manage student data efficiently. The system centralizes essential operations such as enrollment, attendance tracking, academic performance management, and report generation, ensuring robust data security and ease of use.

---

## Key Features

- **Secure Admin Access**:
  - Restricted access for authorized administrators.
  - Role-based authentication ensures data confidentiality.

- **Student Data Management**:
  - Add, update, and delete student profiles.
  - Maintain records of personal, academic, and financial information.

- **Attendance Tracking**:
  - Mark and monitor attendance.
  - Generate detailed attendance reports.

- **Academic Records**:
  - Manage grades and performance data.
  - Generate progress and performance reports.

- **Fee Management**:
  - Track payments and pending dues.
  - Generate invoices and payment reminders.

- **Reports and Analytics**:
  - Generate customizable reports.
  - Analyze trends in attendance and academic performance.

---

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: PHP
- **Database**: MySQL
- **Server**: XAMPP (Apache)

---

## Setup Instructions

1. **Install Prerequisites**
   - Install [XAMPP](https://www.apachefriends.org/) or any compatible web server with PHP and MySQL.

2. **Clone the Repository**
   ```bash
   git clone https://github.com/your-repo/student-information-system.git
   ```

3. **Import the Database**
   - Navigate to `phpMyAdmin` (e.g., `http://localhost/phpmyadmin`).
   - Create a database named `student_system`.
   - Import the `student_system.sql` file located in the project directory.

4. **Configure the Application**
   - Open the `config.php` file in the root directory.
   - Update the database credentials:
     ```php
     define('DB_HOST', 'localhost');
     define('DB_USER', 'root');
     define('DB_PASS', '');
     define('DB_NAME', 'student_system');
     ```

5. **Run the Application**
   - Start the XAMPP server (Apache and MySQL).
   - Open your browser and navigate to `http://localhost/student-information-system`.

6. **Admin Login**
   - Use the default admin credentials:
     - **Username**: `admin`
     - **Password**: `admin123`
   - Change the password after the first login for enhanced security.

---

## Usage

- **Login**: Enter admin credentials to access the dashboard.
- **Manage Data**: Add, update, delete, or view student records.
- **Generate Reports**: Export or analyze data for attendance, grades, and fees.

---

## Security Features

- Password-protected admin login.
- Role-based authentication.
- Sanitized database inputs to prevent SQL injection.

---

## Support

For assistance, contact the developer at [support@yourdomain.com](mailto:support@yourdomain.com).
