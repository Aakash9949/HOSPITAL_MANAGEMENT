LINK: https://aakash9949.github.io/HOSPITAL_MANAGEMENT/

DBMS_CAPSTONE_HOSPITAL
🏥 Hospital Management System (DBMS Project) 📌 Overview

The Hospital Management System (HMS) is a comprehensive database-driven application designed to manage and streamline the operations of a healthcare facility. This system focuses on organizing patient records, doctor information, appointment scheduling, and billing processes in a structured and efficient manner.

Traditional hospital systems rely heavily on manual paperwork, which often leads to data redundancy, errors, and difficulty in retrieving information. This project solves these problems by implementing a Relational Database Management System (RDBMS) using MySQL, ensuring data consistency, integrity, and fast access.

The system models real-world hospital operations and demonstrates key DBMS concepts such as normalization, entity relationships, primary keys, and foreign keys. It provides a simple and user-friendly interface for managing hospital data effectively.

🚀 Features 🧑 Patient Management Add, update, and view patient details Store personal and contact information 👨‍⚕️ Doctor Management Add doctor records Manage specialization and availability 📅 Appointment System Book appointments between patients and doctors Maintain schedule records 💵 Billing System Generate and manage patient bills Track payment status 🔗 Relational Database Design Use of Primary Keys and Foreign Keys Maintains relationships between tables 🔍 Data Retrieval Efficient querying using SQL Easy access to stored records ⚡ User-Friendly Interface Simple web-based forms Easy navigation 🛠️ Tech Stack 💻 Frontend: HTML, CSS 🗄️ Database: MySQL 🧰 Server: MySQL 🗄️ Database Schema

The system uses a structured relational database with the following tables:

📌 Patients (patient_id (Primary Key) name age gender phone address)

📌 Doctors (doctor_id (Primary Key) name specialization phone)

📌 Appointments (appointment_id (Primary Key) patient_id (Foreign Key) doctor_id (Foreign Key) date time)

📌 Billing bill_id ((Primary Key) patient_id (Foreign Key) amount status)

🔄 Entity Relationships . One Patient can have multiple Appointments (1:M) . One Doctor can handle multiple Appointments (1:M) . One Patient can have multiple Bills (1:M)

⚙️ Setup Instructions Open MySQL Workbench Create database

📈 Future Enhancements 🔐 User Authentication (Login System) 📊 Admin Dashboard with Analytics 🔍 Search & Filter Functionality 📄 Report Generation (PDF Bills) 📧 Email/SMS Notifications 🌐 Cloud Deployment

📚 Learning Outcomes Understanding of DBMS concepts and normalization Hands-on experience with MySQL queries Backend integration using PHP Building real-world database applications Managing relational data effectively

Creater

Aakash Yadav B.Tech CSE Student | DBMS Project
