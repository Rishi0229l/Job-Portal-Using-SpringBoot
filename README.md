# Online Job Portal


The Online Job Portal using Spring Boot simple and lightweight job portal application built using Java and Spring Boot. It provides a platform for job seekers to browse and apply for available job listings, while recruiters can post job openings and manage applications



## Overview

The Online Job Portal ensures efficient job management for employers and job seekers. Employers can post job listings with detailed information, and employees can apply for jobs based on their qualifications and preferences. The system facilitates communication and updates between employers, employees, and administrators, streamlining the hiring process.

## Technologies Used

- Java 8
- Spring Boot 
- JWT for user authentication
- PostgreSQL 
- Maven 
- Postman 
- Hibernate
- Swagger (API's Documentation)

## Software Used

- IntelliJ IDEA backend development
- psql terminal-based front-end to PostgreSQL 
- Postman for API's Testing
  
## User Modules

1. **Administrator Module**
   - Login to the system
   - Register other administrators
   - Manage job categories
   - View all jobs and applicants
   - View and manage employers and employees

2. **Employer Module**
   - Register and login to the system
   - Post job listings with detailed information
   - View applicants for posted jobs
   - Update job status for applicants

3. **Employee Module**
   - Register and login to the system
   - Search and view job listings
   - Apply for jobs based on qualifications
   - View and update profile information
   - View applied jobs and status
   - Cancel applied jobs
  
   - POST `/api/auth/login`   - Login and obtain JWT authentication token.
   - POST `/api/auth/signin`  - Register a new user (Employer or Employee).
   - POST `/api/employers` Create new Employer
   - POST `/api/employers/{employerId}/jobs` Create new Job
   - POST `/api/employers/{employerId}/myApplications/{applicationId}` Update Application Status
   - GET `/api/employers` List All Employers
   - GET `/api/employers/{employerId}/jobs` Get All Jobs Posted By Give employer ID
   - GET `/api/employers/{employerId}/myApplications` Get All Applications for Jobs Posted by Employer Id
   - DELETE `/api/employers/{employerId}/jobs/{jobId}` Delete Job by Posted By Employer
  
Run the application:
    - Build and run the Spring Boot application.
    - The application will be deployed locally at http://localhost:8080.
  

