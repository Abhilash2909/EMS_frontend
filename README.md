# EMS_Frontend

This is the frontend part of the Employee Management System (EMS) built using **React.js**. It provides the user interface to manage employee data such as listing, adding, updating, and deleting employee details.

## Project Structure

- `src/`
  - `components/`
    - **EmployeeComponent.jsx**: Displays individual employee details.
    - **FooterComponent.jsx**: A simple footer for the application.
    - **HeaderComponent.jsx**: The header section of the application.
    - **ListEmployeeComponent.jsx**: Lists all the employees with actions like edit and delete.
  - `services/`
    - **EmployeeService.js**: Handles HTTP requests to interact with the backend API for CRUD operations.
  - **App.jsx**: The main entry point that defines the application's structure.
  - **main.jsx**: The file where the app is rendered into the DOM.
  - **App.css**: Contains styles for the application.
  - **index.html**: The main HTML file where the app is injected.
  - **.eslintrc.cjs**: ESLint configuration file.
  
- **package.json**: Lists the project dependencies and scripts.
- **vite.config.js**: Configuration file for Vite, the build tool.
- **.gitignore**: Specifies files to be ignored by git.
- **README.md**: This file.

## How to Run the Application

1. **Install dependencies:**
   ```bash
   npm install
2. **Install dependencies:**
    ```bash
    npm run dev
3. **Open your browser at http://localhost:3000 to view the application.**

## Technologies Used

- **React.js**
- **Vite (Build tool)**
- **JavaScript (ES6+)**
- **CSS (for styling)**
- **Axios (for API requests)**
- **POSTMAN (for testing APIs)**
