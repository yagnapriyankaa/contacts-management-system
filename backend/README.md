
# Contacts Backend

This is the backend for the **Contact Management System**, built with **Spring Boot** and managed via **Gradle**. The backend handles data processing, business logic, and interacts with a **MySQL** database to store contact information. It provides a RESTful API for creating, reading, updating, and deleting contact records.

## Project Features

- **CRUD Operations**: Supports Create, Read, Update, and Delete operations for contacts, accessible through four RESTful APIs.
- **Soft Delete**: Contacts are not permanently removed from the database; they are marked as deleted for data retention.
- **MySQL Database**: Stores contact information and manages data consistency across all CRUD operations.

## Tech Stack

- **Backend**: Spring Boot, Gradle
- **Database**: MySQL

## API Endpoints

1. **Create Contact**: `POST /api/contacts` – Adds a new contact to the database.
2. **Read Contacts**: `GET /api/contacts` – Retrieves a list of all active contacts.
3. **Update Contact**: `PUT /api/contacts/{id}` – Updates an existing contact’s details.
4. **Delete Contact**: `DELETE /api/contacts/{id}` – Marks a contact as deleted.

## Development Setup

### Prerequisites

- Java 17 or higher
- MySQL Database
- Gradle

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/contacts-management-system.git
   ```
2. **Navigate to the backend folder**:
   ```bash
   cd contacts-management-system/backend
   ```
3. **Configure the Database**:
   - Ensure MySQL is running.
   - Update `application.properties` with your MySQL database credentials:
     ```properties
     spring.datasource.url=jdbc:mysql://localhost:3306/your_database_name
     spring.datasource.username=your_username
     spring.datasource.password=your_password
     ```

### Running the Application

Use Gradle to start the Spring Boot application:
```bash
./gradlew bootRun
```
The application will start on `http://localhost:8080/`.

## Testing

To run tests, use:
```bash
./gradlew test
```

## Further Help

For more on Spring Boot, visit the [Spring Boot Documentation](https://spring.io/guides/gs/spring-boot/).
