# Hospital Management System

## Description-
   In this Project we aim to solve the traditional issues of hospital management. The existing system provided paper based solution for keeping OPD records of patients and hospital staff, but it gives overload to Doctor, Receptionist and Administrator.  The main issues were inappropriate data keeping, time wastage in storage, retrieval also patients were unable to understand the prescription etc. These issues are solved by providing a separate user account for doctors and other staff. Keeping each patient’s data separate and track previous visits in a single click. 
   
   This project uses MYSQL as backend and is developed in Java so it provides features such as platform independence, high performance and security. It is a web application which mainly uses SpringMVC and Hibernate frameworks. 
   
   It provides some enhanced features such as: an easy interface to add, remove employees as well as it provides PDF of prescription. Thus, reducing need to manually write  and  sign  by doctor.
   
## Cloud Architecture Diagram

![Cloud Architecture Diagram](https://github.com/akarsh-23/WebArch/blob/master/readme_images/System%20Diagrams/Cloud%20Architecture%20Diagram.png)

## Technologies Used-

### 1. Front end Technologies:
  - HTML
  - CSS
  - Bootstrap
  - JavaScript
  
### 2. Back end Technologies:
  - SpringMVC 
  - Hibernate
  
### 3. Database:
  - MySQL
  
### 4. Project management tool:
  - Maven
  
### 5. Webserver:
  - Apache Tomcat

### 6. Amazon Web Services:
  - Elastic Compute Cloud
  - Virtual Private Cloud
  - Relational Database Service
  - Route53
  - CloudWatch
  - Simple Notification Service
  - Identity and Access Management
  - Elastic Block Storage
  - Simple Storage Service

## Features-
  1. Doctor module:
      - Seperate accounts for doctors
      - Each patients previous visits history is easily to access.
      - Doctor can generate prescription and it will be automatically sent to receptionist.
      - Doctor can remove patient from OPD queue.
      
  2. Receptionist module:
      - Register/add new patient's info.
      - Modify patients personal details
      - Search existing patient by name/ mobile no./ PID/ aadhar no.
      - Remove patient from OPD queue.
      - Take print of prescriptions.
      
  3. Administrator module:
      - Add new employee for following roles,
                      i) Doctor
                     ii) Receptionist
                    iii) Admin (another one)
      - Remove/edit existing employee. 
      - Displays currently active employees in system.
      
  4. Password Encryption:
      - *_Bcrypt Encoding_* is used for password encryption. Bcrypt is a password hashing function designed by Niels Provos and David Mazières. It is based on the Blowfish cipher. Bcrypt uses adaptive hash algorithm to store password. BCrypt internally generates a random salt while encoding passwords and hence it is obvious to get different encoded results for the same string. But one common thing is that everytime it generates a String of length 60.


## Snapshots-

1. Homepage

![Homepage](https://github.com/akarsh-23/WebArch/blob/master/readme_images/snapshots/homepg.png)

2. Login page

![Login page](https://github.com/akarsh-23/WebArch/blob/master/readme_images/snapshots/loginpg.png)

3. Administrator Dashboard

![Administrator Dashboard](https://github.com/akarsh-23/WebArch/blob/master/readme_images/snapshots/adminDashboard.png)

![Administrator All employee view](https://github.com/akarsh-23/WebArch/blob/master/readme_images/snapshots/adminAll.png)

4. Doctor Dashboard

![Doctor Dashboard - patient observation](https://github.com/akarsh-23/WebArch/blob/master/readme_images/snapshots/doctorObservation.png)

![Doctor Dashboard - patient prescription](https://github.com/akarsh-23/WebArch/blob/master/readme_images/snapshots/doctorPrescription.png)

5. Receptionist Dashboard

![Receptionist Dashboard search patient](https://github.com/akarsh-23/WebArch/blob/master/readme_images/snapshots/receptionistSearch.png)

![Receptionist Dashboard add patient to opd](https://github.com/akarsh-23/WebArch/blob/master/readme_images/snapshots/receptionistAdd.png)

## System Diagrams

1. Usecase Diagram

![Usecase Diagram](https://github.com/akarsh-23/WebArch/blob/master/readme_images/System%20Diagrams/Usecase%20Diagram.jpg)

2. Activity Diagram

![Activity Diagram](https://github.com/akarsh-23/WebArch/blob/master/readme_images/System%20Diagrams/Activity%20Diagram.png)

3. Class Diagram

![Class Diagram](https://github.com/akarsh-23/WebArch/blob/master/readme_images/System%20Diagrams/Class%20Diagram.png)

4. Sequence Diagram

![Sequence Diagram](https://github.com/akarsh-23/WebArch/blob/master/readme_images/System%20Diagrams/Sequence%20Diagram.png)

5. State Diagram

![State Diagram](https://github.com/akarsh-23/WebArch/blob/master/readme_images/System%20Diagrams/State%20Diagram.png)

### Thank You !
