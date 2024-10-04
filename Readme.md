# Code Assassin

Code Assassin is an EdTech platform built using the MERN stack that offers interactive courses with video lectures, assessments, and a comprehensive student dashboard. It includes role-based access control for admins, instructors, and students, along with secure payment integration.

## Features

- Interactive courses with video lectures and assessments.
- Role-based access control (RBAC) for admins, instructors, and students.
- Secure payment gateway integration using Razorpay.
- Comprehensive student dashboard to track progress.
- Built with Redux for state management.

## Technologies Used

### Frontend:
- **React.js**
- **Redux** (State Management)
- **Tailwind CSS** (Styling)

### Backend:
- **Node.js**
- **Express.js**
- **MongoDB** (Database)
- **JWT/OAuth** (Authentication)

### Additional Tools:
- **Razorpay** (Payment Gateway)
- **Vercel** (Frontend Hosting)
- **Render** (Backend Hosting)

## Installation

### Prerequisites:
- Node.js
- MongoDB

### Steps to run the project:

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/code-assassin.git
    ```

2. Navigate to the **frontend** and **backend** directories and install the dependencies:

    ```bash
    cd frontend
    npm install

    cd ../backend
    npm install
    ```

3. Create a `.env` file in both the **frontend** and **backend** directories with the necessary environment variables. Example:

    **Backend .env**:
    ```env
    DATABASE_URL=<Your MongoDB URL>
    JWT_SECRET=<Your JWT Secret>
    RAZORPAY_KEY=<Your Razorpay Key>
    ```

    **Frontend .env**:
    ```env
    REACT_APP_API_URL=<Your Backend URL>
    ```

4. Start both the backend and frontend servers:

    **Backend**:
    ```bash
    npm start
    ```

    **Frontend**:
    ```bash
    npm start
    ```

5. Open the application in your browser at `http://localhost:3000` (frontend).

## Contribution

Contributions are welcome! Please follow the [contributing guidelines](CONTRIBUTING.md) if you wish to contribute.

## License

This project is licensed under the MIT License.
