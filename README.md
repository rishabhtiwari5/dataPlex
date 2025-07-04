# DataPlex - People Information Manager

This is a full-stack web application for efficient people information management. The backend is built with Java and Spring Boot, providing a RESTful API, and the frontend is a responsive application built with React.

## Features

*   View a paginated list of all people-related data.
*   Add a new contact with details like name, email, phone, address, and title.
*   Upload a profile photo for each contact.
*   View the details of a specific contact.
*   Update the information for an existing contact.

## Tech Stack

### Backend

*   **Spring Boot**
*   **PostgreSQL**

### Frontend

*   **React**
*   **React Router**
*   **CSS**

## Project Structure

The project is organized into two main directories:

```
/
├── backend/      # Spring Boot REST API source code
└── frontend/     # React SPA source code
```

## Prerequisites

Before you begin, ensure you have the following installed:

*   Java JDK 21 or newer
*   Maven
*   Node.js and npm
*   A running PostgreSQL database instance

## Getting Started

Follow these steps to get the application running on your local machine.

### 1. Backend Setup

First, configure and run the Spring Boot backend.

1.  **Navigate to the backend directory:**
    ```sh
    cd backend
    ```

2.  **Configure the database:**
    Open the [`backend/src/main/resources/application.yml`](backend/src/main/resources/application.yml) file and update the `spring.datasource` properties with your PostgreSQL connection details.

    ```yml
    spring:
      datasource:
        url: jdbc:postgresql://YOUR_DATABASE_HOST:5432/YOUR_DATABASE_NAME
        username: YOUR_POSTGRES_USERNAME
        password: YOUR_POSTGRES_PASSWORD
    ```

3.  **Run the backend application:**
    ```sh
    mvn spring-boot:run
    ```
    The backend server will start on `http://localhost:8080`.

### 2. Frontend Setup

Next, set up and run the React frontend.

1.  **Navigate to the frontend directory:**
    ```sh
    cd frontend
    ```

2.  **Install dependencies:**
    ```sh
    npm install
    ```

3.  **Start the development server:**
    ```sh
    npm start
    ```
    The React application will open in your browser at `http://localhost:3000`.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
