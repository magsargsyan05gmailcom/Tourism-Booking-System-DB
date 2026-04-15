# Tourism-Booking-System-DB
🌍 Tourism and Travel Booking System
📌 Project Overview

This project is a relational database system designed to manage tourism and travel booking operations.
It allows customers to search for travel packages, make bookings, complete payments, and leave reviews, while administrators manage all system data.

🎯 Objectives
Design a structured relational database
Apply normalization up to Third Normal Form (3NF)
Implement SQL queries and operations
Simulate a real-world booking system
🧱 Database Structure
Main Entities
Customer
TravelPackage
Destination
Hotel
Booking
Payment
Review
Relationships
One customer → multiple bookings
One booking → one payment
One package → one destination & hotel
One customer → multiple reviews
⚙️ Technologies Used
SQL (MySQL / SQL Server)
Relational Database Design
ER Modeling
📂 Project Files
File Name	Description
schema.sql	Database structure (CREATE TABLE)
data.sql	Sample data (INSERT statements)
queries.sql	Queries (SELECT statements)
advanced.sql	Views, Indexes, Triggers, Procedures
🔍 Sample Features
Retrieve all customers
Show confirmed bookings
Join multiple tables for detailed results
Filter travel packages by price
🚀 Advanced Features
Views → simplified queries
Indexes → faster search
Triggers → automatic validation
Stored Procedures → reusable operations
📊 Normalization

The database is normalized up to 3NF (Third Normal Form) to:

eliminate redundancy
ensure data integrity
improve efficiency
🧪 Testing
All tables created successfully
Data inserted and validated
Queries tested with JOIN and filtering
Relationships verified
📈 Conclusion

This project demonstrates a complete database system implementation, including design, normalization, and SQL operations.
It can be extended into a full application with a user interface.

👩‍💻 Author

Margarita Sargsyan

📅 Date

April 2025
