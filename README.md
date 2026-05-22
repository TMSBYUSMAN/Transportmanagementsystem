# UOSTMS - University Transport Management System

A comprehensive, dynamic web-based solution designed to streamline and automate university transportation logistics. The system handles transport schedules, bus route optimization, fuel tracking, fee management, student registrations, and complaint ticketing.

## 📸 Project Preview
> <img width="1914" height="846" alt="Screenshot 2026-05-21 230931" src="https://github.com/user-attachments/assets/8fc57593-ecda-41b2-b531-64c09948409b" />


## 🚀 Key Features
* **Multi-Role Authentication:** Secure login and session management for both System Administrators and Students.
* **Dynamic Route & Bus Management:** Interactive tools to add, modify, and monitor active university bus routes and fleets.
* **Driver Records:** Maintain comprehensive profiles and operational schedules for drivers.
* **Automated Fee & Challan Management:** Generate, view, and print student transportation fee cards and challans seamlessly.
* **Complaints Ticketing System:** Students can submit, track, and view complaints regarding transport services, with direct admin review.
* **Asynchronous UX (Ajax):** Powered by Ajax and jQuery for seamless, real-time data submission without reloading pages.

## 🛠️ Tech Stack
* **Frontend:** Bootstrap 5, HTML5, CSS3, JavaScript, jQuery
* **Backend:** PHP (Server-Side Scripting)
* **Database:** MySQL
* **Data Transfer:** Asynchronous Ajax calls

## 🔑 Default Credentials (For Testing & Evaluation)
To evaluate the application without registering a new account, use these pre-configured user credentials:

### 1. Admin Portal
* **Email / Username:** `admin@uostms.com`
* **Password:** `admin123`

### 2. Student Portal
* **Email / Username:** `student@uostms.com`
* **Password:** `student123`

## 📂 Project Architecture & File Structure
The project repository follows a structured layout, separating functional modules:

```text
UOSTMS/
├── uploads/                  # Directory for user-uploaded documents and profile media
├── add_bus.php              # Interface to allocate and append new buses to the system
├── add_route.php            # Route creation and mapping dashboard
├── auth.php                  # Centralized backend session verification
├── dashboard.php            # Main layout wrapper for the management console
├── dashboard_content.php    # Dynamic metrics, statistics, and charts layout
├── db_connect.php            # Core MySQL database connection handler
├── db_update.php            # Script managing asynchronous database updates
├── drivers.php               # Driver directory and assignment logs
├── fees.php                  # Fee status ledger and monitoring module
├── fuel_management.php      # Fuel consumption logs and expense tracking
├── git-helper.bat            # Automation script for Git repository backups
├── header.php                # Global reusable navigation bar and header dependencies
├── index.php                 # Application landing and entry page
├── login.php                 # Admin authorization portal entry
├── logout.php                # Flushes active sessions and safely redirects users
├── maintenance.php          # Vehicle maintenance logging tool
├── print_card.php           # Formatted print view for student transport identity cards
├── print_challan.php        # Generates printable fee challan invoices
├── register.php              # New user and student registration handling
├── reports.php               # Data generation module for operations and revenue reports
├── student_dashboard.php     # Simplified dedicated portal for logged-in students
├── student_login.php         # Student authentication interface
├── student_logout.php        # Secure sign-out utility for student accounts
├── students.php              # Master database viewer and editor for student profiles
├── style.css                 # Custom core application styles overriding Bootstrap
├── submit_complaint.php      # Form to file a transport grievance
├── track_complaint.php       # Live status tracker for filed complaints
├── university_tms.sql        # Database schema blueprint and seed data export
└── view_complaints.php       # Admin console to resolve incoming student complaints
