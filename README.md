# CS 465 – Module Eight Journal Reflection

## Architecture

Throughout this project, I worked with multiple frontend technologies, each serving a different purpose. The customer-facing portion of the application used Express with HTML templates to render pages on the server. This approach was straightforward and well suited for displaying travel information to users. The administrative side of the application was built as a Single-Page Application (SPA) using Angular. Unlike the Express pages, the SPA dynamically updates content without requiring full page reloads, creating a faster and more responsive experience for administrators. JavaScript and TypeScript were used throughout the application to add functionality, handle user interactions, and communicate with the backend API.

The backend used a MongoDB NoSQL database because it stores information as flexible JSON-like documents instead of fixed tables. This made it easy to store travel package information with varying fields and allowed the application to exchange data seamlessly between the frontend and backend. MongoDB also integrates well with Node.js and Mongoose, making it an effective choice for a JavaScript-based full stack application.

## Functionality

JSON (JavaScript Object Notation) is a lightweight data format used to exchange information between systems. Although it resembles JavaScript object syntax, JSON is purely a data format and cannot contain functions or executable code. In this project, JSON served as the communication layer between the Angular frontend, Express backend, and MongoDB database. API responses returned JSON data, which Angular used to display and update trip information.

Throughout the development process, I refactored code several times to improve organization, readability, and maintainability. I created reusable Angular components such as trip cards, trip listings, navigation, and authentication features instead of duplicating code. I also implemented reusable services for API communication and JWT authentication. These reusable UI components made the application easier to maintain, reduced duplicated code, and allowed updates to be made in a single location instead of multiple files.

## Testing

Testing a full stack application involves verifying that API endpoints correctly process requests and return the expected responses. Throughout this project, I tested HTTP methods such as GET, POST, PUT, and DELETE to ensure trips could be retrieved, created, updated, and removed successfully. I also verified that API endpoints communicated properly with the MongoDB database.

After implementing JWT authentication, testing became more complex because secured endpoints required valid authentication tokens before allowing access. This added an additional layer of security that protected administrative functions from unauthorized users. Understanding how methods, endpoints, authentication middleware, and tokens work together gave me valuable experience with building secure web applications.

## Reflection

This course significantly expanded my understanding of full stack web development and helped me move closer to my professional goal of becoming a software engineer. Before this course, I had experience writing code in individual programming languages, but I had not built a complete application that connected a frontend, backend, database, and authentication system.

Throughout this project, I strengthened my skills in JavaScript, TypeScript, Angular, Node.js, Express, MongoDB, RESTful APIs, JWT authentication, and GitHub version control. I also gained experience debugging complex issues involving routing, API communication, database models, and authentication. Building a complete full stack application from start to finish has given me confidence working across the entire software development stack and provided a strong portfolio project that demonstrates practical experience to future employers.

