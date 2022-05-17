
  # E-Commerce Back End (ORM)
  
  This application uses Sequelize and MySQL to host the product and stock information for an e-commerce website. The application uses API requests to handle data and products, categories, and product tags can be created, viewed, updated, and created.
  
  ## Table of Contents
  
  * [Installation](#installation)
  * [Built With](#built)
  * [Usage Information](#usage)
  * [Authors & Acknowledgements](#credits)
  * [Contact](#questions)
  
  ## Installation <a name="installation"></a>
  After cloning the repository, enter "npm i" to install all runtime dependencies. This application is solely a backend application and only hosts database information and API routes.
  
  ## Built With <a name="built"></a>
  * JavaScript
  * Node.js
  * Express.js
  * npm sequelize
  * npm dotenv
  * npm mysql2
  * Insomnia

  ## Usage Information<a name="usage"></a>
  This application is suitable for basic product, stock, and pricing management.</br>
  Video walkthrough of how to use this application, [here](https://drive.google.com/drive/folders/1D-TSKg4Vlpj5NHZcqJjckin9SbiqzSUn?usp=sharing).</br>
  </br>![E-Commerce Back End (ORM)](./e-commerce.png "E-Commerce Back End (ORM)")</br>
  
  ## Authors & Acknowledgements<a name="credits"></a>
  
  Base code © 2020 - 2022 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.
  
  Made by [TOVTC](https://github.com/TOVTC).</br>
  Originally submitted 2022May17.
  
  ## Questions?<a name="questions"></a>
  Contact repository author via [GitHub](https://github.com/TOVTC).</br>

    ## Assignment Information - Object-Relational Mapping (ORM) Challenge: E-commerce Back End
  ### User Story
  AS A manager at an internet retail company</br>
  I WANT a back end for my e-commerce website that uses the latest technologies</br>
  SO THAT my company can compete with other e-commerce companies
  
  ### Acceptance Criteria
  GIVEN a functional Express.js API</br>
  WHEN I add my database name, MySQL username, and MySQL password to an environment variable file</br>
  THEN I am able to connect to a database using Sequelize</br>
  WHEN I enter schema and seed commands</br>
  THEN a development database is created and is seeded with test data</br>
  WHEN I enter the command to invoke the application</br>
  THEN my server is started and the Sequelize models are synced to the MySQL database</br>
  WHEN I open API GET routes in Insomnia for categories, products, or tags</br>
  THEN the data for each of these routes is displayed in a formatted JSON</br>
  WHEN I test API POST, PUT, and DELETE routes in Insomnia</br>
  THEN I am able to successfully create, update, and delete data in my database</br>
    