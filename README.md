# EmployWise Assignment

This project is a React application that integrates with the Reqres API to perform basic user management functions.

## Features

- Authentication with email and password
- Paginated list of users
- CRUD operations on users
- Search functionality
- Responsive design
- Protected routes
- Toast notifications

## Tech Stack

- React
- TypeScript
- Tailwind CSS
- React Router DOM
- Axios
- React Hot Toast
- Zustand (State Management)

## Getting Started

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```

## Login Credentials

- Email: eve.holt@reqres.in
- Password: cityslicka

## Project Structure

- `/src/components` - Reusable components
- `/src/pages` - Page components
- `/src/store` - State management
- `/src/App.tsx` - Main application component

## Features Implemented

### Level 1: Authentication Screen
- Login form with email and password
- Token storage in local storage
- Protected routes

### Level 2: List All Users
- Paginated list of users
- Display user details in a card format
- Pagination controls

### Level 3: Edit, Delete, and Update Users
- Edit user details
- Delete users
- Success/error notifications

### Bonus Features
- Client-side search
- React Router for navigation
- Responsive design