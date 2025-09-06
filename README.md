#  Clinic Booking System (MySQL Database)

##  Overview
This project is a **Clinic Booking System database** implemented in MySQL.  
It manages patients, doctors, appointments, and treatments with proper relationships.

##  Schema Design
- **Patients**: Stores patient details.  
- **Doctors**: Stores doctor details and specializations.  
- **Appointments**: Links patients with doctors and stores appointment info.  
- **Treatments**: Stores available treatments and their costs.  
- **Appointment_Treatments**: Junction table for many-to-many relationship between appointments and treatments.

##  Features
- **Primary Keys**: Ensure entity uniqueness.  
- **Foreign Keys**: Enforce referential integrity.  
- **Constraints**: NOT NULL, UNIQUE, ENUM for data consistency.  
- **Relationships**:  
  - Patients ↔ Appointments → One-to-Many  
  - Doctors ↔ Appointments → One-to-Many  
  - Appointments ↔ Treatments → Many-to-Many  
