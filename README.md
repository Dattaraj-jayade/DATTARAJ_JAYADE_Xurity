# NAME_Xurity

## CRUD website with MERN 

This is an CRUD website built with React and Node.js. It allows users to register, log in, and manage their expenses. Administrators can manage users from the admin panel.

## Technologies Used

- React
- Node.js
- Express
- MongoDB
- Ant Design
- Bootstrap

## Features

- User registration and login
- Role-based access control (admin and user)
- Admin panel for managing users
- Responsive UI built with Bootstrap
- Spinner component for loading states
## Installation

Follow these steps to set up the project locally.

### Prerequisites

- Node.js
- npm 
- MongoDB

### Steps

1. **Clone the repository:**

    ```sh
    git clone https://github.com/your-username/expense-management-system.git
    cd expense-management-system
    ```

2. **Install dependencies for the client:**

    ```sh
    cd client
    npm install
    ```

3. **Install dependencies for the server:**

    ```sh
    cd ../server
    npm nodemon
    npm install
    ```

4. **Set up environment variables:**

    Create a `.env` file in the root of the server directory and add your MongoDB connection string.

    ```plaintext
    MONGO_URL=mongodb+srv://your-mongodb-connection-string
    ```

5. **Run the server:**

    ```sh
    npm run dev
    ```
   # if it didn't work
   
   **Run the server:**
   ```sh
   npm start
   ```

   **Run the client:**

    Open a new terminal window and navigate to the `client` directory:

    ```sh
    cd client
    npm start
    ```
    After registration go to `MongoDB` and change the
   
   ```sh
   isAdmin:false
   ```
     to
   ```sh
    isAmin :true
   ```
    then he will be the admin
