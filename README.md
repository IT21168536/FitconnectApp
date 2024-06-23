
```markdown
# Fitness Enthusiast Social Media Platform

## Overview

This project involves the development of a social media platform tailored for fitness enthusiasts to share their fitness journeys, workouts, and healthy lifestyle tips. The platform consists of two main components:

- REST API: Built using Java (Spring Boot) to handle backend functionalities.
- Client Web Application: Developed using React to provide an interactive interface for users.

## Features

### User-Generated Content

- **Posts**: Users can upload up to 3 photos or 30-second videos showcasing their fitness activities.
- **Workout Status Updates**: Share updates on current workouts with predefined templates.
- **Workout Plan Sharing**: Create and share workout plans, including routines and exercises.
- **Meal Plan Sharing**: Share meal plans with recipes and nutritional information.

### User Interaction

- **Liking and Commenting**: Interact with posts by liking and commenting, with edit/delete functionalities.
- **Profiles**: View and follow other users' profiles, displaying all fitness-related posts and activities.
- **Notifications**: Receive notifications for likes and comments on posts.

### User Management

- **Social Login**: Allow users to log in using existing social media accounts.
- **Edit/Delete Posts**: Users can edit or delete their posts and comments.

## Tech Stack

### Backend

- Spring Boot : Framework for building the REST API.
- Spring Security: For handling authentication and authorization.
- JPA/Hibernate: For database interactions.
- MySQL: Database for storing user data and posts.

### Frontend

- React: Library for building the user interface.
- Redux: State management for the application.
- Axios: For making HTTP requests to the REST API.
- Material-UI: For UI components and styling.

## Getting Started

### Prerequisites

- Java 11+
- Node.js 
- MySQL

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/fitness-social-media-platform.git
    cd fitness-social-media-platform
    ```

2. **Backend Setup**:
    - Navigate to the backend directory:
        ```bash
        cd backend
        ```
    - Configure the database in `application.properties`:
        ```properties
        spring.datasource.url=jdbc:mysql://localhost:3306/pafdb?
        spring.datasource.username=root
        spring.datasource.password=yourpassword
        ```
    - Build and run the Spring Boot application:
        ```bash
        mvn clean install
        mvn spring-boot:run
        ```

3. **Frontend Setup**:
    - Navigate to the frontend directory:
        ```bash
        cd ../frontend
        ```
    - Install dependencies and start the React application:
        ```bash
        npm install
        npm start
        ```

## API Endpoints

### Authentication

- **POST /api/auth/login**: User login.
- **POST /api/auth/register**: User registration.

### Posts

- GET /api/posts: Retrieve all posts.
- POST /api/posts: Create a new post.
- PUT /api/posts/{id}: Update a post.
- DELETE /api/posts/{id}: Delete a post.

### Comments

- POST /api/posts/{postId}/comments: Add a comment to a post.
- PUT /api/comments/{id}: Update a comment.
- DELETE /api/comments/{id}: Delete a comment.

### Users

- GET /api/users/{id}: Retrieve user profile.

- GET /api/users/{id}/posts: Retrieve posts by user.
- POST /api/users/{id}/follow: Follow a user.
- POST /api/users/{id}/unfollow: Unfollow a user.

This corrected version ensures that headings, bullet points, and code blocks are properly formatted, making the `README.md` file readable and visually appealing.



![Screenshot 2024-06-20 232031](https://github.com/IT21168536/FitconnectApp/assets/99183326/4f263191-1710-4b6a-afad-dc4d7167ac30)
![Screenshot 2024-06-20 232044](https://github.com/IT21168536/FitconnectApp/assets/99183326/33463aef-899b-4518-8b3c-73920a34c403)
![Screenshot 2024-06-20 221338](https://github.com/IT21168536/FitconnectApp/assets/99183326/08df9de9-1d06-40aa-a852-8e2e89c3e207)
![Screenshot 2024-06-20 231923](https://github.com/IT21168536/FitconnectApp/assets/99183326/4001b27a-382e-4548-8b7a-01cd845de069)
![Screenshot 2024-06-20 231818](https://github.com/IT21168536/FitconnectApp/assets/99183326/48724683-9ce7-4a65-881b-d04486b47b6f)
![Screenshot 2024-06-20 221311](https://github.com/IT21168536/FitconnectApp/assets/99183326/6a8e021e-9ff3-4d7e-b930-4978241de38f)
![Screenshot 2024-06-20 220839](https://github.com/IT21168536/FitconnectApp/assets/99183326/543f6a7b-3836-47ce-a132-68bb57585678)
