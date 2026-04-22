# cs465-fullstack
CS-465 Ful Stack Development with MEAN

**Overview**

Travlr Getaways is a full stack web application that supports both a customer-facing experience and an administrative interface. Users can browse travel packages on the public side, while administrators can securely log in to manage trip data.

This project brings together frontend development, backend APIs, database integration, and authentication into a single working system.

**Architecture**

This application uses two frontend approaches: server-rendered pages with Express and a single-page application (SPA) built with Angular. The Express side uses Pug templates to render HTML on the server, which is efficient for initial page loads. The Angular SPA, used for the admin side, provides a more dynamic experience by updating content without full page reloads and allowing reusable components.

The backend is built with Node.js and Express, exposing RESTful API endpoints consumed by both frontends. MongoDB was used as the database because its flexible, JSON-like document structure integrates naturally with JavaScript, making it easier to manage and transfer data across the stack.

**Functionality**

JSON is the standardized format used to transfer data between the frontend and backend, while JavaScript objects are used within the application itself. This allows the frontend to send requests and easily parse responses from the backend, creating a consistent communication layer.

During development, I refactored code to replace outdated dependencies, improve API structure, and reduce redundancy. Angular components allowed me to reuse UI elements and logic, which improved maintainability, reduced duplication, and created a more consistent user experience.

**Testing**

I used Postman to test API endpoints by sending GET, POST, PUT, and DELETE requests to verify functionality and ensure correct status codes were returned. This helped confirm that each endpoint performed the expected action and handled data properly.

With authentication added, testing also included verifying secure access using JSON Web Tokens (JWTs). I ensured that protected routes required valid tokens and that unauthorized users were restricted, which reinforced my understanding of security in full stack applications.

**Reflection**

This course helped me move closer to my goal of becoming a full stack developer by giving me hands-on experience building a complete application. I developed skills in working with APIs, structuring applications, integrating databases, and troubleshooting real-world issues across the stack.

One of my biggest takeaways is increased confidence. While this project was guided, I now feel more prepared to build my own applications independently and continue developing projects using the MEAN stack.

**Technologies Used**
- Angular
- Node.js
- Express
- MongoDB (Mongoose)
- Bootstrap
- JSON Web Tokens (JWT)
- Postman
- Heroku

**Future Improvements**

Future improvements could include enhancing the user interface, adding customer account functionality, and improving validation and error handling. I would also expand the API to support more advanced filtering and search features.
