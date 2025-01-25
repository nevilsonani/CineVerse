# Cineverse

Cineverse is a full-stack web application built using the MERN (MongoDB, Express, React, Node.js) stack. It serves as a platform for movie enthusiasts to explore, review, and discuss movies.

## Features

- **User Authentication**: Sign up, log in, and manage your profile.
- **Browse Movies**: Search and explore a collection of movies with detailed descriptions.
- **Movie Reviews**: Leave reviews and ratings for movies.
- **Interactive UI**: A responsive and intuitive user interface.
- **Admin Panel**: Manage movies, reviews, and users (admin-only feature).

## Technologies Used

### Frontend
- **React**: For building the user interface.
- **Redux**: For state management.
- **Tailwind CSS**: For styling.

### Backend
- **Node.js**: For server-side scripting.
- **Express**: For building the REST API.

### Database
- **MongoDB**: For data storage.

### Others
- **JWT**: For user authentication and authorization.
- **Axios**: For API requests.
- **Mongoose**: For MongoDB object modeling.

## Installation and Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/nevilsonani/cineverse.git
   ```

2. Navigate to the project directory:
   ```bash
   cd cineverse
   ```

3. Install dependencies for both client and server:
   ```bash
   cd client
   npm install
   cd ../server
   npm install
   ```

4. Configure environment variables:
   - Create a `.env` file in the `server` directory.
   - Add the following:
     ```env
     MONGO_URI=your-mongodb-uri
     JWT_SECRET=your-jwt-secret
     PORT=5000
     ```

5. Start the development servers:
   - Run the backend server:
     ```bash
     cd server
     npm run dev
     ```
   - Run the frontend server:
     ```bash
     cd client
     npm start
     ```

6. Open the app in your browser at `http://localhost:3000`.


## License

This project is licensed under the [MIT License](LICENSE).

