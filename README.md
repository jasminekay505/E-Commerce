# E-Commerce Back End Example
![License: ICL](https://img.shields.io/badge/License-ISC-blue.svg)

This application provides the back-end for an e-commerce site. The user can perform the following actions: 
- Connect to database after adding MySQL username and SQL password to .env  
- Enter schema and seed commands to create database and seed it with data  
- Automatically connect to server with the start command
- View all products, categories or tags with a GET request
- View a single product, category or tag with a GET request
- Add a product, category, or tag with a POST request
- Update a product, category, or tag with a PUT request
- Delete a product, category or tag with a DELETE request

## Link to video demonstration of application usage
https://drive.google.com/file/d/1rQyrZTEJ5OmQrqTFq8v8DoTY43hszbKk/view

## Installation
- Command: *npm i*

## Usage
1. Update MySQL username and SQL password in .env.EXAMPLE
    - Rename file to .env
2. Install dependencies
    - Command: *npm i*
3. Create the database from command line (or use MySQL workbench)
    - Command: *mysql -u root -p*
    - Enter MySQL password
    - Command: *source db/schema.sql*
4. Seed database
    - Command: *npm run seed*
5. Start the application
    - Command: *npm start* 
6. Use Insomnia core to GET, POST, PUT or DELETE data
7. CRTL+C to Exit

## Technologies Used
- MySQL
- Insomnia
- Node
    - Express.js
    - Sequelizer
    - dotenv

## Screenshots
![image](https://user-images.githubusercontent.com/74380703/112381109-6f51f000-8ca7-11eb-9445-3ca43ef00c4a.png)

## License
ISC

## Author Contact Info
*jasminekay505@gmail.com*