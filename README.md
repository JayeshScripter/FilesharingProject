FileSharingApp

Filesharingapp is a Spring Boot application that allows users to upload and share files. It uses MySQL as the database and is built with Java 17 and Spring Boot 3.2.2.


Features
 Secure file upload & download
 Unique file links for sharing
 Expiry-based file access



Tech Stack
 Java (Spring Boot)
 MySQL
 REST APIs



API Endpoints
POST /upload → Upload file
GET /download/{fileId} → Download file
