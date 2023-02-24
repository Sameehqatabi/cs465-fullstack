# cs465-fullstack
CS-465 Full Stack Development with MEAN

#Architecture
Compare and contrast the types of frontend development you used in your full stack project, including Express HTML, JavaScript, and the single-page application (SPA).
Express HTML and JavaScript are commonly used for server-side rendering of dynamic web pages. This approach requires a full page refresh for each user interaction, resulting in slower page load times and reduced user experience. On the other hand, Single-Page Applications (SPAs) use JavaScript frameworks like Angular to dynamically update only the required parts of the page, resulting in faster response times and a more fluid user experience. SPAs use APIs to communicate with the backend and can retrieve and display data without refreshing the entire page. In a full stack web application, both approaches can be used, with server-side rendering for certain pages and SPAs for others, depending on the requirements of the application.

Why did the backend use a NoSQL MongoDB database?
The backend used a NoSQL MongoDB database because it is a flexible and scalable database that can handle large volumes of unstructured data. MongoDB's document-based model allows for easy storage and retrieval of complex data structures, making it a good fit for web applications that require dynamic and changing data. Additionally, MongoDB's scalability allows for horizontal scaling, making it easier to handle increased traffic and data growth without sacrificing performance.

#Functionality
How is JSON different from Javascript and how does JSON tie together the frontend and backend development pieces?
JSON is a data format that is similar to JavaScript objects but with a simpler syntax. While JavaScript objects are used for writing executable code, JSON is used for data transfer between the frontend and backend of a web application. JSON acts as a common language that ties together the frontend and backend development pieces by providing a standard format for data exchange. The backend can send data in JSON format, and the frontend can receive it and parse it into JavaScript objects for further use. Similarly, the frontend can send data to the backend in JSON format, and the backend can receive it and convert it into a format that can be stored in a database or used for other backend processing.

Provide instances in the full stack process when you refactored code to improve functionality and efficiencies, and name the benefits that come from reusable user interface (UI) components.
An example of code refactoring was when I improved the security of the application by implementing password hashing using bcrypt. This helped to improve the overall security of the application and reduce the risk of a security breach.

#Testing
Methods for request and retrieval necessitate various types of API testing of endpoints, in addition to the difficulties of testing with added layers of security. Explain your understanding of methods, endpoints, and security in a full stack application.
Endpoints are specific URLs that the client can send requests to, using HTTP methods such as GET, POST, PUT, and DELETE. These endpoints can be used to retrieve, add, modify or delete data from the backend database. API testing is important in ensuring that these endpoints are functioning properly and returning expected results. Testing can can be done with postman. Security is also a critical aspect of API testing, as the data transmitted between the frontend and backend should be protected from unauthorized access. This can be achieved by implementing authentication and authorization controls such as tokens, API keys, or OAuth.

#Reflection
How has this course helped you in reaching your professional goals? What skills have you learned, developed, or mastered in this course to help you become a more marketable candidate in your career field?
By learning how to build a complete web application from scratch, from designing the front-end UI to creating a backend API & database, and various web technologies, such as HTML, CSS, JavaScript, Node.js, Express, and MongoDB. I also gained experience with software development best practices, testing, debugging, and deployment.
These skills make me more marketable in their career field by giving me hands-on experience with the tools and technologies that companies use to build web applications. I also learned skills that are transferable to other programming languages and frameworks, such as problem-solving, logic, and critical thinking. By the end of the course, I have a project that I can showcase to potential employers, demonstrating my skills and experience in full stack web development.


