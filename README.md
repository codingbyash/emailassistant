
# Email Writer

This project is a Spring Boot-based email writer application that includes various modules for creating and sending emails. The project also features a React frontend and an extension for additional functionalities.

## Project Structure

The project is structured into several directories, each handling different aspects of the application:

- `email-writer-ext`: The extension module that adds extra features to the email writer.
- `email-writer-react`: The React-based frontend for the email writer application.
- `email-writer-sb`: The core Spring Boot application responsible for handling backend functionalities such as email generation and sending.
- `hello-world-ext`: A basic extension module for testing purposes.

## Requirements

- JDK 17 or above (for running the Spring Boot application).
- Node.js and npm (for running the React frontend).
- Maven (for building the Spring Boot application).

## Getting Started

### Backend Setup (Spring Boot)

1. Navigate to the `email-writer-sb` directory:
   ```bash
   cd email-writer/email-writer-sb
   ```

2. Build and run the Spring Boot application:
   ```bash
   mvn clean install
   mvn spring-boot:run
   ```

   This will start the backend service at `http://localhost:8080`.

### Frontend Setup (React)

1. Navigate to the `email-writer-react` directory:
   ```bash
   cd email-writer-react
   ```

2. Install the dependencies:
   ```bash
   npm install
   ```

3. Start the React development server:
   ```bash
   npm start
   ```

   This will launch the React frontend at `http://localhost:3000`.

### Running the Project

- Once both the backend and frontend are running, you can access the email writer application by navigating to `http://localhost:3000` in your browser.
- The React frontend will communicate with the Spring Boot backend to create and send emails.

## Testing

The project includes unit and integration tests for the Spring Boot application. You can run the tests using Maven:

```bash
mvn test
```

## Contributing

Feel free to fork the repository and submit pull requests for new features or bug fixes. When contributing, please ensure that you follow the existing code style and write tests for any new functionality.

