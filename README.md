# ORMchall-E-commerce
# SQL-challenge-employee-tracker

## Description

This back-end application serves as the core for an e-commerce platform, built with Express.js and powered by Sequelize to seamlessly manage a PostgreSQL database. It provides the foundational API needed to manage products, categories, tags, and their associations, enabling e-commerce functionality.
Since this application is not deployed, a walkthrough video has been created to demonstrate its functionality and confirm that all acceptance criteria are met.

## Table of Contents (Optional)

- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Installation

Follow these steps to set up and run the e-commerce back-end project locally:

1. **Clone the Repository**  
   First, clone the repository to your local machine using the following command:

   ```bash
   git clone https://github.com/Nikky0910/ORMchall-E-commerce
    ```
2. **Navigate to the Project Directory**  
   After cloning, navigate to the project directory:

   ```bash
   cd ORMchall-E-commerce
    ```
3. **Install Dependencies**  
    Install the required Node.js packages by running:

   ```bash
   npm install
    ```
    This will install the following dependencies:
    -**dotenv**: Loads environment variables from a .env file into process.env, keeping sensitive information secure.
    -**express**: A web framework for building a robust API and handling HTTP requests and routing.
    -**pg**: The PostgreSQL client for Node.js, used to interact with the database.
    -**sequelize**: An ORM library for Node.js that simplifies database management with models, associations, and queries.

4. **Set Up Enviroment Variables**  
    Create a .env file in the root directory and configure it with the following variables:
     ```bash
     DB_USER="postgres"
     DB_PASSWORD= "your_password"
     DB_NAME="ecommerce_db"
     ```
     Replace your DB_USER, DB_PASSWORD and DB_NAME with your PostgreSQL database credentials.

5. **Run the database** 
    Navigate to the db folder through the terminal and run the schema by typing:
    ```bash
   psql -U postgres
   \i schema.sql
   \c ecommerce_db;
    ```
6. **Start the server**  
   Launch the application by running:

   ```bash
   npm start
    ```
    The server should start on  http://localhost:3001 or the port specified in your environment variables.

7. **Test the API**
   Use a tool like Insomnia, Postman, or cURL to test the API endpoints for products, categories, tags, and associations.

## Usage

Please refer to the following video on how to test the api endpoints using Insomnia: 

<a href = "https://drive.google.com/file/d/1V_M42tEqaGuADHuEFivhkFzLZIspZyZC/view?usp=sharing"> Click here to watch the video</a>

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
