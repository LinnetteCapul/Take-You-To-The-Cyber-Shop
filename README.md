# Take You To The Cyber Shop

  ## Description
  A back end application for an e-commerce website that allows to store, update, and delete data in order to organize their product inventory more efficiently. The purpose of this application is allow an e-commerce website to use the latest technolgies so that they can compete with other e-commerce companies.

  
  ## Table of Contents
  
  * [Links](#links)
  * [Installation](#installation)
  * [Usage](#usage)
  * [Contribution Guidelines](#contribution-guidelines)
  * [Tests](#tests)
  * [Questions](#questions)
  * [Screenshots](#screenshots)


  ## Links
  

 * GitHub Repository Link: https://github.com/LinnetteCapul/Take-You-To-The-Cyber-Shop

 * Demonstration Video: https://drive.google.com/file/d/1LgRV2qDbHxyTB4NGwjHCFqAPrrKDpPqK/view
  
  ## Installation
  
  To use this application, the user will need to fork the repository. The user will also need to have MySQL Workbench, Insomnia or Postman installed as well as need to install (`npm i`) the necessary packages for the applicaton to run accordingly.
  
  ## Usage
  
  When a user adds their database name, MySQL username, and MySQL password to an environment variable file, they are able to connect to a database using Sequelize. After entering schema and seed commands, a development database is created and is seeded with test data. When either `npm run start` or `node server.js` is invoked in the command line, then the server is started and the Sequelize models are synched to the MySQL database. When the user opens API GET routes in Insomnia for categories, products, or tags, then teh data for each of these routes are displayed in a JSON format. When the user tests API POST, PUT, or DELETE routes in Insomnia, then they are able to successfully able to create, update or delete the data in the database. 

  
  ## Contribution Guidelines
  
  For details on how to contribute to this project, please reach out to the original creator of the project. Contact information can be found under “Questions?” section.
  
  ## Tests
  
  * Seed Data: `npm run seed`
  * Run Server: `npm run start`
  
  
  ## Questions?
  
  Please contact me at either of the following for any inquiries about the project.

  * GitHub Profile: [LinnetteCapul](https://github.com/LinnetteCapul)
  * Email: linnette.capul@gmail.com

  ## Screenshots
  
  ![cyber-shop-screenshot01](https://raw.githubusercontent.com/LinnetteCapul/Take-You-To-The-Cyber-Shop/main/assets/cyber-shop-screenshot01.JPG)
  
  Example of GET route for `/api/categories` in Insomnia displaying data in JSON format.

  
  <br>
  
  ![cyber-shop-screenshot02]()

  Example of POST route for `/api/tags` in Insomnia displaying data in JSON format.
