# Spring Boot Event API

This project is a Spring Boot application that connects to an H2 in-memory database. It provides a simple API for managing events.

## Features

- In-memory H2 database for quick setup and testing.
- RESTful API for creating, retrieving, and listing events.
- H2 console enabled for easy database management.

## Getting Started

### Prerequisites

- Java 11 or higher
- Maven

### Running the Application

1. Clone the repository:
   ```
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```
   cd springboot-event-api
   ```

3. Build the project using Maven:
   ```
   mvn clean install
   ```

4. Run the application:
   ```
   mvn spring-boot:run
   ```

5. Access the H2 console at:
   ```
   http://localhost:8080/h2-console
   ```
   Use the following credentials:
   - JDBC URL: `jdbc:h2:mem:testdb`
   - User Name: `sa`
   - Password: `password`

### API Endpoints

- `POST /events` - Create a new event
- `GET /events/{id}` - Retrieve an event by ID
- `GET /events` - Retrieve all events

## License

This project is licensed under the MIT License.