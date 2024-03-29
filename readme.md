## Project Management Web App with Node.js, GraphQL, MongoDB, and React
This project is a web application for managing projects and clients. It utilizes a modern tech stack:

#### Backend: 
Node.js server with MongoDB as database and GraphQL for a flexible and efficient API.
#### Frontend: 
ReactJS for a user-friendly and dynamic interface.
#### Data: 
Apollo Client for seamless interaction with the GraphQL API.


### The application revolves around two main entities:

- Clients: Users can create and manage client profiles with basic details.
- Projects: Each client can have multiple associated projects. Users can create, view, and edit project details.


### Key features include:

- Project creation and management: Create, edit, and delete projects associated with clients.
- Detailed project views: View specific project information alongside associated client details.
- Optimized data handling: InMemoryCache in the frontend reduces unnecessary database calls during delete operations.
- This project showcases the power of modern web development tools for building interactive and data-driven applications.

#### Home page:

![Alt text](image.png)

#### Add a Client

![Alt text](image-1.png)

#### Add a New Project

![Alt text](image-2.png)

#### Project Detail Page

![Alt text](image-3.png)

#### Commands used for front-end

- npm i express express-graphql graphql mongoose cors colors
- npm i -D nodemon dotenv    
- npm run dev
- Server runs on port 8000
- GraphQL UI can be accessed at localhost:8080/graphql

#### Commands used for backend

- npx create-react-app client
- npm i @apollo/client graphql react-router-dom react-icons
- npm start
- Client runs on port 3000

Tutorial Link: https://youtu.be/BcLNfwF04Kw?feature=shared