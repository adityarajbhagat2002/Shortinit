# URL Shortening Application

## Overview

This application allows users to shorten URLs and manage them efficiently. It follows the MVC architecture pattern for better organization and scalability.

URL : https://arb-sh.onrender.com/login

## Technologies Used

- Node.js
- Express.js
- MongoDB
- EJS (Embedded JavaScript) for templating

## Installation and Setup

1. Clone the GitHub repository:

2. Navigate to the project directory:

3. Install dependencies:

4. Set up environment variables:

- Create a `.env` file in the root directory.
- Define variables like `MONGODB_URI` for MongoDB connection and other necessary configurations.

## Running the Application

1. Start the server:
2. Access the application in your browser at `http://localhost:3000`.

## Functionality

### 1. User Authentication

- **Signup:** Users can sign up for an account providing necessary details.
- **Login:** Registered users can log in securely using their credentials.
- **Logout:** Users can log out of their accounts.

### 2. URL Shortening

- **Shorten URL:** Authenticated users can shorten long URLs, generating a unique short URL.
- **View Shortened URLs:** Users can view a list of their shortened URLs along with original links.
- **Delete Shortened URL:** Users can delete any of their shortened URLs if needed.

### 3. Database Integration

- **MongoDB:** Utilized MongoDB for storing and retrieving shortened URLs and user information.
- **Optimized Performance:** Implemented database optimizations for better performance.

## MVC Architecture

- **Models:** Define schemas for users and URLs, handle database operations.
- **Views:** Use EJS templates for rendering dynamic content.
- **Controllers:** Handle user requests, interact with models, and render appropriate views.

## Security

- **Secure Authentication:** Implemented secure user authentication with cookies for seamless login and signup functionalities.
- **Data Protection:** Ensured data protection measures are in place to prevent security vulnerabilities.

## Deployment

- The application is deployed on a scalable platform ensuring availability and reliability.

## Conclusion

This URL shortening application provides a robust solution for managing and shortening URLs efficiently. With its scalable architecture and secure authentication mechanisms, it ensures a seamless user experience while maintaining data integrity and security.
