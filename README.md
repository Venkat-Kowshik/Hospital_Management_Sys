# Hospital Management System

## <u>Project Overview</u>
The **Hospital Management System** is a robust, web-based application designed to streamline hospital operations. It enables doctors and administrators to efficiently manage their respective tasks through secure, role-based dashboards. The project focuses on automating hospital processes, minimizing manual errors, and improving workflows.

---

## <u>Key Features</u>

### Doctor Dashboard
- View the list of patients currently under treatment.
- Access detailed diagnostic data for individual patients.
- Perform CRUD (Create, Read, Update, Delete) operations for patient management.
- Manage hospital medicines, with options to add or update entries.

### Admin Dashboard
- View a list of patients (non-sensitive details only).
- Perform CRUD operations to manage appointments.

---

## <u>Technical Scope</u>
- **Frontend**: Angular 14  
- **Backend**: Spring Boot  
- **Database**: MySQL8  
- **API Communication**: RESTful APIs  
- **Real-Time Notifications**: WebSocket integration  

---

## <u>High-Level Design</u>

### Architectural Overview
The application follows the **MVC (Model-View-Controller)** architecture for modular, scalable, and maintainable development.

### Frontend
- Built with **Angular 14** using Angular CLI for scaffolding.
- Implements:
  - Dynamic routing via `RouterModule`.
  - Two-way data binding using `[(ngModel)]`.
  - Reactive forms powered by `FormBuilder`.
- API communication is managed through Angular services.

### Backend
- Developed using **Spring Boot**.
- **JPA/Hibernate** is used for database communication.
- RESTful APIs support HTTP methods: `GET`, `POST`, `PUT`, `DELETE`.
- Includes WebSocket for real-time notifications.
- Ensures security with **CORS policies**.

### Database
- Built on **MySQL8** with tables for:
  - Patients
  - Doctors
  - Medicines
  - Appointments

---

## <u>How to Run the Application</u>

### Prerequisites
- **Frontend:**
  - Node.js 16 or later
  - Angular CLI
- **Backend:**
  - Java 17
  - Maven
- **Database:**
  - MySQL8 or compatible database server

### Setup Steps
1. Clone the repository:
   ```bash
   git clone git@github.com:Venkat-Kowshik/Hospital_Management_Sys.git
   cd Hospital_Management_Sys
Frontend Setup:

Navigate to the frontend directory:
bash
Copy code
cd frontend
npm install
ng serve
Backend Setup:

Navigate to the backend directory:
bash
Copy code
cd backend
mvn clean install
mvn spring-boot:run
Database Setup:

Import the provided schema or create the tables in MySQL as defined in the project.
Access the application:

Frontend: http://localhost:4200
Backend API Documentation (Swagger): http://localhost:8080/swagger-ui.html


---

   
