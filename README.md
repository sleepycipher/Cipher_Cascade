# CipherCascade: A Multi-Layer Encryption Framework
The CipherCascade application is designed to provide users with a robust, multi-layered encryption platform for securing sensitive data. It allows users to register, authenticate, encrypt/decrypt messages using multiple cascading algorithms (AES, DES, Blowfish), and persistently store encrypted data in a relational database — providing a comprehensive security toolkit for data protection and cryptographic learning.

Technologies Used:

Component      	Technology
Programming Language	Java (OOP + JDBC)
GUI Framework	Java Swing
Database	MySQL
Encryption Libraries	Java Cryptography Extension (JCE)
IDE	IntelliJ IDEA / link Eclipse
JDK Version	Java SE 8+
 
Database Overview

Database: cipherdb
All tables are linked with foreign keys and support ON DELETE CASCADE for data consistency.
The app uses two main tables:
•	cipher_users: stores user profiles and authentication credentials 
•	encrypted_data: records encrypted texts, algorithms used, and timestamps per user




Key Features

•	User registration and login with validation 
•	Multi-algorithm cascade encryption system (AES, DES, Blowfish) 
•	Flexible algorithm selection and combination 
•	Secure key-based encryption/decryption 
•	Persistent storage of encrypted data in MySQL 
•	User-specific data isolation and management 
•	Interactive data table with CRUD operations 
•	Real-time encryption/decryption with visual feedback 
•	Database schema viewer for transparency 
•	Clean and responsive Swing GUI using CardLayout 
•	Session management with logout functionality
Core Concepts Implemented

•	Object-Oriented Programming (Classes, Encapsulation, Inheritance)
•	JDBC Database Connectivity for MySQL integration 
•	Exception Handling and Input Validation for robust error management 
•	Event-driven GUI Programming with ActionListeners 
•	Cryptographic Operations using Java Cipher and SecretKeySpec 
•	Base64 Encoding/Decoding for data representation 
•	Modular design with clear separation of UI and logic 
•	Secure Authentication System with user sessions 
•	CardLayout Navigation for multi-screen applications 
•	TableModel Management for dynamic data display

Encryption Algorithms Supported

1.	AES (Advanced Encryption Standard) - 128-bit symmetric encryption 
2.	DES (Data Encryption Standard) - 56-bit legacy encryption 
3.	Blowfish - Variable-length key symmetric cipher
Learning Outcomes
•	Developed full-stack understanding using Java and MySQL 
•	Mastered cryptographic operations with Java Cipher API 
•	Strengthened skills in Swing GUI design and JDBC connectivity 
•	Gained experience in managing relational databases 
•	Learned to design an end-to-end application architecture 
•	Implemented secure authentication and session management 
•	Practiced modular programming with separation of concerns 
•	Enhanced understanding of symmetric encryption algorithms 
•	Developed skills in event-driven programming 
•	Learned database normalization and foreign key relationships
