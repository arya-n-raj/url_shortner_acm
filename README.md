# url_shortner_acm


                                

                                    URL Shortener

## Project Description
This project is a simple URL shortener that takes a long URL as input and generates a shortened URL. It also provides the functionality to redirect users from the shortened URL to the original URL.

## How to Run the Project
1. Clone the repository:
                             git clone https://github.com/arya-n-raj/url_shortner_acm.git



2. Navigate to the project directory:may vary in future hence not added


3. Install dependencies:
The project relies on the following npm packages:
- [express](https://www.npmjs.com/package/express): Fast, unopinionated, minimalist web framework for Node.js.
- [mongoose](https://www.npmjs.com/package/mongoose): Elegant MongoDB object modeling for Node.js.
- [ejs](https://www.npmjs.com/package/ejs): Embedded JavaScript templates for server-side rendering.
- [nodemon](https://www.npmjs.com/package/nodemon): Development tool that automatically restarts the Node.js server when file changes are detected.

Make sure you have Node.js and npm (Node Package Manager) installed on your machine before running the above command.

4. Start the server:npm start devStart in this case

5. Access the URL shortener in your browser at: `http://localhost:3000`

## Internal Working
In the URL shortener project, there are three main components: the server, the database, and the hashing algorithm.

Server: The server is built using Node.js and Express.js. It serves as the backbone of the application, handling incoming requests from clients and generating shortened URLs. It also handles the redirection of users from the shortened URLs to the original URLs. The server utilizes the Express.js framework to define routes, handle HTTP methods, and send responses to the clients.

Database: The project uses a database to store the mappings between the shortened URLs and the original URLs. In this case, MongoDB is chosen as the database system. MongoDB is a NoSQL database that provides a flexible and scalable solution for storing and retrieving data. It offers a document-oriented data model, which is well-suited for this project's requirements. To interact with the MongoDB database, the project utilizes Mongoose, an Object Data Modeling (ODM) library for Node.js and MongoDB. Mongoose simplifies the interaction with the database by providing a higher-level abstraction, allowing developers to define schemas, models, and perform CRUD (Create, Read, Update, Delete) operations.

Hashing Algorithm: A hashing algorithm is used to generate unique short URLs from the original URLs. In this project, a basic hashing algorithm is used as an example. Hashing is a process that takes an input (in this case, the original URL) and produces a fixed-size string of characters, which is the shortened URL. The generated hash should be unique and irreversible, meaning it cannot be used to obtain the original URL. While a basic hashing algorithm can be used for simplicity, in a production environment, a more robust and collision-resistant algorithm, such as SHA-256 or bcrypt, should be employed to ensure the uniqueness and security of the shortened URLs.

Overall, the combination of the server, database, and hashing algorithm allows the URL shortener project to generate and store unique shortened URLs while efficiently redirecting users to the original URLs when requested.
## Learning Takeaways
Through the URL shortener project, I gained valuable experience in building a web application using Node.js and Express.js. I learned how to implement URL shortening functionality by utilizing hashing algorithms, integrate a MongoDB database with Mongoose for efficient data modeling and interaction, handle HTTP requests and responses effectively, and deploy the application to a production environment. This project provided me with a comprehensive understanding of the key components involved in developing a web application, from server-side programming to database integration, ultimately enhancing my skills in full-stack development.

## Resources/References
- [Express.js documentation](https://expressjs.com/)
- [Node.js documentation](https://nodejs.org/)
- [MongoDB documentation](https://docs.mongodb.com/)
- [Mongoose documentation](https://mongoosejs.com/)
- [Hashing Algorithms in JavaScript](https://www.sitepoint.com/hashing-passwords-in-javascript/)


## npm Packages
The project relies on the following npm packages as dependencies:
- [express](https://www.npmjs.com/package/express): Fast, unopinionated, minimalist web framework for Node.js.
- [mongoose](https://www.npmjs.com/package/mongoose): Elegant MongoDB object modeling for Node.js.
- [ejs](https://www.npmjs.com/package/ejs): Embedded JavaScript templates for server-side rendering.
- [nodemon](https://www.npmjs.com/package/nodemon): Development tool that automatically restarts the Node.js server when file changes are detected.

//////////Make sure you have Node.js and npm (Node Package Manager) installed on your machine before running the above command.

Please note that this README assumes the repository is available at https://github.com/arya-n-raj/url_shortner_acm. If the repository location is different, please update the URL accordingly.

Feel free to customize the README file based on your specific implementation and requirements.//////////



This README file provides comprehensive information about the project, including the project description, installation instructions, internal working, learning takeaways, resources/references used, and the required npm packages. You can further modify the content as needed for your specific project.




- last edit-21/06/2023 00:01
- 


