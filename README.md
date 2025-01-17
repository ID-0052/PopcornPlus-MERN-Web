# MERN Movie App Documentation

## Project Objectives & Goals
The objective of this project is to create a movie website called "Popcorn+" that allows users to add, search, and view details of movies. The website aims to provide a user-friendly interface for movie enthusiasts to explore a collection of movies, add new movies, and view detailed information about each movie.

## Technologies Used
This project is built using the MERN stack, which includes the following technologies:

- **MongoDB**: A NoSQL database used to store movie data.
- **Express.js**: A web application framework for Node.js used to build the backend API.
- **React**: A JavaScript library for building user interfaces, used for the frontend.
- **Node.js**: A JavaScript runtime used to build the backend server.
- **Axios**: An HTTP client for making API requests.
- **React Router**: A library for handling routing in React applications.
- **Vite**: A build tool that provides a fast development environment for modern web projects.
- **Vercel**: A platform for deploying and hosting web applications.

## Design & Development Process
1. **Planning**: Define the project objectives, goals, and requirements. Create a project plan and timeline.
2. **Setup**: Set up the project structure, initialize the frontend and backend, and configure necessary tools and libraries.
3. **Backend Development**: Implement the backend API using Express.js and MongoDB. Create models, routes, and controllers for handling movie data.
4. **Frontend Development**: Implement the frontend using React. Create components for the homepage, movie details page, and movie creation form. Integrate the frontend with the backend API using Axios.
5. **Styling**: Apply CSS styles to the frontend components to create a visually appealing user interface.
6. **Testing**: Test the application to ensure it works as expected. Fix any bugs or issues that arise.
7. **Deployment**: Deploy the application to a live server using Vercel.

## Challenges Faced & Solutions Implemented
- **Challenge**: Handling asynchronous API requests and managing state in React.
  - **Solution**: Used the `useEffect` and `useState` hooks to manage state and handle side effects in React components.
  
- **Challenge**: Ensuring smooth navigation and routing in the React application.
  - **Solution**: Used React Router to handle client-side routing and navigation.
  
- **Challenge**: Deploying the backend and frontend to a live server.
  - **Solution**: Used Vercel to deploy both the backend and frontend, ensuring proper configuration for API routes and static file serving.

## Project Deployment Details

### Deploying to Vercel
1. **Commit your code to Git.**
2. **Create a Vercel account**:
   - Sign up on the [Vercel website](https://vercel.com/).
3. **Import the repository**:
   - Go to the Vercel dashboard.
   - Click on "New Project" and import your Git repository.
4. **Deploy the backend**:
   - Select the backend directory (e.g., `movie-backend`) as the root directory for the backend project.
   - Set up the necessary environment variables (e.g., `MONGO_URI`) in the Vercel dashboard.
   - Click "Deploy" to deploy the backend.
5. **Deploy the frontend**:
   - Select the frontend directory (e.g., `frontend`) as the root directory for the frontend project.
   - Click "Deploy" to deploy the frontend.

By following these steps, you can successfully deploy the "Popcorn+" movie website to a live server using Vercel.
