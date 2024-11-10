# Contact Management System

## Overview
This project is a full-stack contact management system developed during my internship. The system enables users to add, view, update, and delete contact information with ease. It includes a frontend built with Angular and Angular Material for a clean, responsive UI, and a backend developed with Spring Boot, following RESTful principles for efficient data handling.

## Features
- **Frontend**:
  - Built with **Angular** and **Angular Material components** for a sleek and responsive user interface.
  - **Add Contact**: A button opens a reactive form with fields for name, phone number, email, etc., each validated to ensure data integrity.
  - **Search Functionality**: A client-side search allows users to filter contacts by any field, making it easy to locate specific information quickly.
  - **Contacts Table**: Displays contact information, including name, phone number, and email, with actions like:
    - **Update**: Edit existing contact information.
    - **Delete**: Remove a contact (soft delete).
    - **View Details**: An eye icon allows users to view additional contact details on a separate page, enabled through Angular routing.
    
- **Backend**:
  - Developed with **Spring Boot** and **Gradle**, following REST API principles.
  - Includes **four REST APIs** for performing CRUD (Create, Read, Update, Delete) operations on contacts.
  - **Soft Delete**: Contacts are not permanently removed from the database but marked as deleted for data retention.

- **Database**:
  - Uses **MySQL** to store contact data securely, supporting the soft delete feature and ensuring data consistency across CRUD operations.

## Tech Stack
- **Frontend**: Angular, Angular Material
- **Backend**: Spring Boot, Gradle
- **Database**: MySQL

## Installation and Usage
1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/contacts-management-system.git
   ```
2. **Navigate to the backend and frontend folders** to set up each component.
3. **Run the application** by following the specific instructions in each folder’s README file.

## Project Structure
- **Frontend Folder**: Contains Angular files for the UI and client-side logic.
- **Backend Folder**: Contains Spring Boot files, REST APIs, and database configurations.

