# Social Media Project

A comprehensive social media platform developed using the MERN stack, offering a range of features for users and administrators.

## Table of Contents

- [Features](#features)
  - [User Authentication](#user-authentication)
  - [Post Management](#post-management)
  - [User Profiles](#user-profiles)
  - [Administrative Functionalities](#administrative-functionalities)
  - [Real-Time Features](#real-time-features)
- [Technologies Used](#technologies-used)
  - [Backend](#backend)
  - [Frontend](#frontend)
- [Usage](#usage)
- [Installation](#installation)
- [Contributing](#contributing)
- [License](#license)

## Features

### User Authentication

Users can:

- Login using email
- Logout
- Recover forgotten passwords

### Post Management

Users can:

- Upload posts
- View posts
- Like posts
- Comment on posts
- Share posts
- View like and comment counts
- Delete their own posts

### User Profiles

Users can:

- View their profiles
- Edit their profiles
- See following and followers lists
- Search for other users
- View other users' profiles
- View other users' posts
- Follow and unfollow other users
- Search for other users

### Administrative Functionalities

Admins can:

- Login and logout
- View all user lists
- Search for users
- View each user's profile
- View each user's posts
- Delete posts and user

### Real-Time Features

- Real-time updates for likes and comments using **Socket.io**

### Additional User Interaction

Users can:

- Share posts with a URL to non-logged-in users

## Technologies Used

### Backend

- **MongoDB**: NoSQL database for user data, posts, and other information.
- **Express.js**: Backend web application framework for handling HTTP requests and routes.
- **Node.js**: JavaScript runtime environment for server-side development.
- **Express-session**: Middleware for handling user sessions.
- **Helmet**: Middleware to enhance Express app security by setting various HTTP headers.
- **Nodemailer**: Module for sending emails to users, e.g., for password reset functionality.
- **Bcrypt**: Library for hashing and salting passwords to enhance security.
- **Socket.io**: Library for real-time, bidirectional, and event-based communication.

### Frontend

- **React**: JavaScript library for building dynamic and responsive user interfaces.
- **React Bootstrap**: Popular front-end framework for creating a visually appealing UI.
- **Axios**: Promise-based HTTP client for making API requests.
- **Fuse.js**: Fuzzy-search library for efficient and flexible searching.
- **React Icons**: Collection of customizable SVG icons for React applications.

## Usage

1. Clone the repository:

```bash
git clone https://github.com/your-username/social-media-project.git
cd social-media-project
