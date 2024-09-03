# EasyTasks built on top of Ruby on Rails + React

This is a CRUD application built with Ruby on Rails for the backend and React for the frontend. The application allows users to sign up, log in, and manage their todos.

## Features

- User Authentication (Signup, Login)
- Create, Read, Update, Delete (CRUD) Todos
- User can login and create, edit, delete, set status of todos.

## Prerequisites

Before you begin, ensure you have the following installed:

- Ruby (version 2.7 or above)
- Rails (version 6.0 or above)
- Node.js (version 12 or above)
- PostgreSQL

## Screenshots

![Login](https://drive.google.com/uc?export=view&id=1HJmAHqgzZrZOZa006MNOjQsqJ7Wnwefv)
![Sign Up](https://drive.google.com/uc?export=view&id=1_YLyr3cS8TMRrvwS5lbgIk4nH2Mlwpcd)
![Dashboard](https://drive.google.com/uc?export=view&id=1m0_fJqK1wxlD38bOivCyYz7clolM2CmI)
![Tasks](https://drive.google.com/uc?export=view&id=15cB6Te6CcYS0cjNGZ6iUTMQMzezTJt2R)


## Setup Instructions

### Backend (Rails API)

1. **Clone the repository**

    ```sh
    git clone https://github.com/adityasinghbaghel/CRUD-App/tree/main
    cd your-repo-name/backend/app
    ```

2. **Install gems**

    ```sh
    bundle install
    ```

3. **Set up the database**

    ```sh
    rails db:create
    rails db:migrate
    ```

4. **Run the Rails server**

    ```sh
    rails server
    ```

### Frontend (React)

1. **Navigate to the frontend directory**

    ```sh
    cd ../frontend
    ```

2. **Install dependencies**

    ```sh
    npm install
    ```

3. **Start the React application**

    ```sh
    npm start
    ```

### Running the Application

- The Rails server will run on `http://localhost:4000`.
- The React frontend will run on `http://localhost:3000`

