# E-Commerce Back End Application &nbsp; ![MIT License](https://img.shields.io/badge/license-MIT-green)
    
## Description

This ecommerce application allows the user to easily manage their inventory with a mysql database.

[VIDEO WALKTHROUGH](https://youtu.be/YZdMO9BuHjc)

![Screenshot of the application in insomnia](./assets/images/Screen%20Shot%202022-05-05%20at%209.41.40%20PM.png)

## Table of Contents

* [Installation](#installation)
* [Usage](#usage)
* [License](#license)
* [Contributing](#contributing)
* [Tests](#tests)
* [Questions](#questions)

## Installation

This application requires the installation of [node.js](https://nodejs.org/), [npm express](https://www.npmjs.com/package/express), [npm dotenv](https://www.npmjs.com/package/dotenv), [npm sequelize](https://www.npmjs.com/package/sequelize), and [npm mysql2](https://www.npmjs.com/package/mysql2) before use.

1. In this directory, creat a file called '.env' and enter your enter your database credentials in this format:
```md
DB_NAME=ecommerce_db
DB_USER=your mysql username
DB_PASSWORD=your mysql password
```
2. Next, from the terminal, navigate to this directory install all the necessary npm packages.
3. Navigate to the 'db' directory, ogin to your mysql and create your database with the 'source schema.sql' command.
4. Navigate back to this directory and run the 'npm run seed' script to seed your new database.
5. Then run the 'npm run watch' to start the server.
6. Open an API client, such as insomnia, and submit a GET request to http://localhost:3001/api/products to test your connection.
    * If the connection was successful, you should see the seeded product data displayed as a JSON object.

## Usage

1. Open an API client, such as Insomnia.
2. All actions will go through your local host, starting with http://localhost:3001.

### Categories

1. To find all catagories, submit a GET request to /api/categories.
2. To find a specific catagory, submit a GET request to /api/categories/'the category id' (ex: http://localhost:3001/api/categories/3).
3. To add a category, submit a POST request to /api/categories.
4. To update a category, submit a PUT request to /api/categories/'the category id' (ex: http://localhost:3001/api/categories/3).
5. To delete a category, submit a DELETE request to /api/categories/'the category id' (ex: http://localhost:3001/api/categories/3).

### Products

1. To find all products, submit a GET request to /api/products.
2. To find a specific product, submit a GET request to /api/products/'the product id' (ex: http://localhost:3001/api/products/3).
3. To add a product, submit a POST request to /api/products.
4. To update a product, submit a PUT request to /api/products/'the product id' (ex: http://localhost:3001/api/products/3).
5. To delete a product, submit a DELETE request to /api/products/'the product id' (ex: http://localhost:3001/api/products/3).

### Tags

1. To find all tags, submit a GET request to /api/tags.
2. To find a specific tag, submit a GET request to /api/tags/'the tag id' (ex: http://localhost:3001/api/tags/3).
3. To add a tag, submit a POST request to /api/tags.
4. To update a tag, submit a PUT request to /api/tags/'the tag id' (ex: http://localhost:3001/api/tags/3).
5. To delete a tag, submit a DELETE request to /api/tags/'the tag id' (ex: http://localhost:3001/api/tags/3).


## License

MIT License

Copyright &copy; 2022 Team Profile Generator

## Contributing

* node.js
* npm express
* npm sequelize
* npm mysql2

## Tests

Extensive use case tests were performed on every function of this application.

## Questions

[mreliwood on GitHub](https://github.com/mreliwood) &nbsp; | &nbsp; [contact.eliwood@gmail.com](mailto:contact.eliwood@gmail.com)