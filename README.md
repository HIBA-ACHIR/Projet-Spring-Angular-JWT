## Projet Spring Angular JWT

This project is a full-stack application built with Spring Boot (for the backend) and Angular (for the frontend). It features JWT-based authentication and is designed to manage e-banking operations.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- **Java JDK 11 or later**: The backend is built with Spring Boot, which requires JDK 11 or later.
- **Node.js and npm**: The frontend is built with Angular, which requires Node.js and npm.
- **Maven**: To build and manage the Spring Boot project.
- **MySQL**: The project is configured to use a MySQL database.

## Setup Instructions

### Backend Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/Projet-Spring-Angular-JWT.git](https://github.com/HIBA-ACHIR/Projet-Spring-Angular-JWT.git
   cd Projet-Spring-Angular-JWT
   ```

2. **Configure the MySQL database:**
   - Create a database named `ebanking` in your MySQL server.
   - Update the `application.properties` file located in `src/main/resources/` with your MySQL username and password.

3. **Build the backend:**
   ```bash
   mvn clean install
   ```

4. **Run the backend:**
   ```bash
   mvn spring-boot:run
   ```
   The backend should now be running on `http://localhost:8080`.

### Frontend Setup
1. **Navigate to the frontend directory:**

   (Assuming the Angular frontend is located in a subdirectory like `frontend`)

   ```bash
   cd frontend
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Run the frontend:**
   ```bash
   ng serve
   ```

   The frontend should now be running on `http://localhost:4200`.

## Usage
- Access the application by opening `http://localhost:4200` in your browser.
- You can perform operations like creating accounts, making transactions, and viewing account histories.

## Contributing
1. Fork the repository.
2. Create your feature branch: `git checkout -b feature/YourFeature`.
3. Commit your changes: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature/YourFeature`.
5. Open a pull request.
