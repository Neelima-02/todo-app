# Todo Web Application

A full-stack Todo Web Application where users can manage their daily tasks by storing them and updating their status. The application supports user authentication, task management, and profile management.

## Technologies Used:
- **Frontend**: ReactJS
- **Backend**: Node.js, Express
- **Authentication**: JWT (JSON Web Tokens)
- **Database**: SQLite3 or MongoDB
- **Unique ID Generation**: UUID

## Functional Features:
### 1. User Authentication:
- **Signup**: Users can register by providing necessary details like email and password.
- **Login**: Users can log in and authenticate using JWT tokens.
- **JWT Security**: All sensitive API routes are secured using JWT tokens to ensure only authenticated users can access them.

### 2. Todo Management:
- **CRUD Operations**: Users can create, read, update, and delete tasks.
- **Task Status**: Users can update the status of their tasks, with the available statuses being:
  - "done"
  - "pending"
  - "in progress"
  - "completed"

### 3. User Profile Management:
- **Profile CRUD**: Users can manage their profile information such as name, email, and password.
- **Profile Security**: Profile updates are accessible only to the authenticated user.

## Installation & Setup:

### Prerequisites:
Make sure you have the following installed on your local machine:
- Node.js (v14 or later)
- npm (Node package manager)
- MongoDB or SQLite3 (based on your choice)

### 1. Clone the repository:
Clone the repository to your local machine using the following command:
```bash
git clone https://github.com/Neelima-02/todo-app.git
cd todo-app
# todo-app
todo application
