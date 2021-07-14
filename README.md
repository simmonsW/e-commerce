# E-Commerce Back End
  
  ## Table of Contents
  * [Description](#description)
  * [Technologies used](#technologies_used)
  * [Installation](#installation)
  * [How to Use](#How-to-use)
  * [Demo](#Demo)
  * [Collaborators](#collaborators)
    
  ## Description
  This is a standalone back-end application for an e-commerce site built using Node.js. The working Express.js API has now been updated to use Sequelize to interact with a MySQL database.

  ## Technologies used
  * JavaScript
  * Node.js
  * Sequelize
  * MySQL
  * MYSQL2
  * Express.js
  * dotenv

  ## Installation
  Clone this repo to wherever you want on your machine. Once cloned, navigate to the root of the project in the command line. From there, run the command `npm install` or `npm i` to install our dependencies.

  Once the dependencies have been installed, you must create a `.env` file. Still at the root of the project, use the command `touch .env` to create the file. Next, run `open .env` to open the new `.env` file. Add the following, replacing `DB_USER` and `DB_PW` with your own MySQL username and password:

  ```js script
      DB_NAME='ecommerce_db'
      DB_USER='(your mysql username)'
      DB_PW='(your mysql password)'
  ```
  After that's been created, we need to initialize the database. To do so, log in to mySQL in the command line, entering your mysql password when prompted.  Initialize the database with the command `source db/schema.sql` followed by the command `quit;` to close the mysql interface. Lastly, run `npm run seed` to seed the database with the pre-made data. Now we're ready to use the application.

  ## How to Use
  Once dependencies have been installed, run the command `node server.js` from the root of the project. Check out this video to see an example of how to interact with the application using Insomnia Core.

  ## Demo
  Check out the following demo videos!

  Set up database, and server start:
  https://youtu.be/v8X-fF46-Kg

  Category routes:
  https://youtu.be/A-yFfR70WZA

  Product routes:
  https://youtu.be/MaHuSFAkcN8

  Tag routes:
  https://youtu.be/S7ztY6dnMB0

  ## Collaborators
  Wyatt Simmons, Xander Rapstine (for the starter codebase)
