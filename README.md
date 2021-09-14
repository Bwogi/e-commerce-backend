# e-commerce-backend 
  <p align="left">
    <img src="https://img.shields.io/github/repo-size/bwogi/e-commerce-backend" />
    <img src="https://img.shields.io/github/languages/top/bwogi/e-commerce-backend"  />
    <img src="https://img.shields.io/github/issues/bwogi/e-commerce-backend" />
    <img src="https://img.shields.io/github/last-commit/bwogi/e-commerce-backend" >   
  </p>

  ## User Story
  AS A manager at an internet retail company
  I WANT a back end for my e-commerce website that uses the latest technologies
  SO THAT my company can compete with other e-commerce companies
  ## Description
 Internet retail, also known as e-commerce, is the largest sector of the electronics industry, having generated an estimated US$29 trillion in 2017 (Source: United Nations Conference on Trade and Development). E-commerce platforms like Shopify and WooCommerce provide a suite of services to businesses of all sizes. Due to the prevalence of these platforms, developers should understand the fundamental architecture of e-commerce sites. Your challenge is to build the back end for an e-commerce site. You’ll take a working Express.js API and configure it to use Sequelize to interact with a MySQL database.

  ## Packages used
  Node, Express, dotenv, sequelize, mysql2, MySQL

  ## Starting point - database schema
   ![Screenshot](./database_schema.png)

  ## Installation
  ### Clone the project source code
  ### Connect to MySQL database
  With your own database credentials;
  ```$ mysql -u root -p``` 
  ### Create the database schema
  ```mysql> source db/schema.sql;```
  ### Exit the database
  ```mysql> exit```
  ### Populate the database
  ```$ npm run seed```

  ### Start the server
  ```$ npm start```

  ## Starting the mysql server
  With your own database credentials;
  ``` $ mysql -u <your username> -p ```
   ##  Usage
  ```$ npm start ```
  ## License 
  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)<br />
  This app is covered under MIT license.
  
  ## Screenshot
   ![Screenshot](./e-commerce-backend-demo-screenshot.png)
  ## Demo
  Find the [demo here on youtube.](https://youtu.be/MiY-PcK8FZI)
  ## Project repository 
  https://github.com/bwogi/e-commerce-backend
  ## Contributors
  Developed by Andrew Bwogi