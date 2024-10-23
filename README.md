# Sector-6.0

This is my first project based on the MERN stack (MongoDB, Express, React, Node.js). Below is a detailed guide on the features, libraries used, and the setup process for the project.

## Features

- **User Authentication**: Secure login and signup functionality with JWT.
- **Real-time Chat**: Implemented using Socket.IO for real-time communication.
- **File Uploads**: Users can upload images and files using Cloudinary.
- **Responsive Design**: The frontend is designed to be responsive and user-friendly.
- **Data Validation**: Input validation using Joi and express-validator.
- **Email Notifications**: Users receive email notifications for various actions.

## Libraries Used

### Backend
- **Express**: Web framework for Node.js.
- **Mongoose**: ODM for MongoDB.
- **Socket.IO**: For real-time web socket communication.
- **Cloudinary**: For image and file uploads.
- **Bcrypt**: For hashing passwords.
- **JWT**: For secure token-based authentication.
- **Nodemailer**: For sending emails.
- **Winston**: For logging.
- **dotenv**: For managing environment variables.

### Frontend
- **React**: JavaScript library for building user interfaces.
- **Redux**: State management library.
- **Axios**: For making HTTP requests.
- **React Router**: For routing in React applications.
- **React Toastify**: For notifications.
- **Bootstrap Icons**: For icons.

## Setup Process

### Prerequisites
- Node.js and npm installed on your machine.
- MongoDB instance (either local or cloud).

### Backend Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/the-shoaib2/Sector-6.0.git
   cd Sector-6.0/backend
   ```

2. **Install Dependencies**:
   ```bash
   npm install
   ```

3. **Create a `.env` File**:
   Copy the contents of `.env.examples` to a new file named `.env` and update the values as necessary.

4. **Start the Server**:
   ```bash
   npm start
   ```

### Frontend Setup

1. **Navigate to the Frontend Directory**:
   ```bash
   cd ../frontend
   ```

2. **Install Dependencies**:
   ```bash
   npm install
   ```

3. **Start the React Application**:
   ```bash
   npm start
   ```

### Accessing the Application
- The backend will be running on `http://localhost:8080`.
- The frontend will be accessible at `http://localhost:3000`.

## Conclusion
This project serves as a comprehensive example of building a full-stack application using the MERN stack. Feel free to explore the code and modify it as per your requirements.