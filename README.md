# Travl Overview
_This document serves as an overview of the Travlr web application. We will go into detail on the architecture, functionality, and testing procedures of the project._

### Architecture

For this web application I integrated different types of front-end development to create an immersive experience for our users. I started with Express HTML that's static but client-facing. In order to remedy that the Express HTML is converted into an .hbs (handlebars) view to optimize rendering speeds. Javascript is used for both the front and backend, for the frontend we use JS to add dynamic elements to an otherwise static page like fetching data from our Mongo database. I used an SPA architecture approach because the entire webpage because of quick loading times, seamless user experience, and ease in building a feature-rich application. For the backend I utilized a MongoDB database because mongo utilizes JSON schemas and that synergizes extremely well with JS because that's how JS transfers data as well.

### Functionality

Javascript is the actual programming language I used to build the Travlr project but JSON is a way to format JS data into an object and transfer it from the frontend to the backend or vice-versa. An instance of refactored code is when I took the the current Express HTML travel file and refactored it to an .hbs view. This way the refactored code can be used anytime we want to display the travel webpage instead of having to code it in every time.

### Testing

The initial test for testing out API endpoints is by going to your localhost address and test if the endpoints load up. For a full-stack application like this, testing HTTP requests like GET, POST, PUT, DELETE are what determine the functionality of the application. These endpoints also modify the database by retrieving, pushing and modifying data in the database. Speaking of the database, security is an added layer of authentication and authorization that prevents any user from making an unauthorized request but also allows authorized users the requests they need to make within the application.

### Reflection

This course helped me tremendously in my career development. It's extremely helpful being able to experience a full-stack workflow and at the same time also develop a project I could display on my portfolio. One of the key fundamentals I was missing is how the frontend and backend speak to each other in order to create a full-fledged application and this course really helped me solidify that lesson.