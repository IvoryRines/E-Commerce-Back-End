# Ivory E-Commerce Back End

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description

This project is a backend application for an e-commerce site, developed using the current technologies. It leverages Express.js for the server, Sequelize for ORM, and PostgreSQL for the database. The application includes models for products, categories, tags, and product tags with associations, and provides full CRUD operations for these models through RESTful API routes.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Walkthrough Video](#walkthrough)
- [License](#license)
- [Contributing](#contributing)
- [Questions](#questions)

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/IvoryRines/ivory-e-commerce-backend.git
   cd e-commerce-backend
   ```
2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Set up environment variables:**
   Create a '.env' file in the root directory and add your PostgreSQL credentials:
   ```makefile
   DB_NAME='ecommerce_db'
   DB_USER='postgres'
   DB_PASSWORD='your_password'
   ```
4. **Create the database:**
   Use the schema file to create your database in PostgreSQL:

   ```bash
   cd db
   psql -U postgres
   enter your password
   \i schema.sql
   \q
   cd ..
   ```

5. **Seed the database:**
   ```bash
   npm run seed
   ```

## Usage

1. **Start the server:**

   ```bash
   npm run start
   ```

2. **Access API Endpoints:**
   Use a tool like Insomnia or Postman to interact with the API. These are the possible Routes you may access:

- Categories
  - GET /api/categories: Get all categories.
  - GET /api/categories/:id: Get a single category by id.
  - POST /api/categories: Create a new category.
  - PUT /api/categories/:id: Update a category by id.
  - DELETE /api/categories/:id: Delete a category by id.
- Products
  - GET /api/products: Get all products.
  - GET /api/products/:id: Get a single product by id.
  - POST /api/products: Create a new product.
  - PUT /api/products/:id: Update a product by id.
  - DELETE /api/products/:id: Delete a product by id.
- Tags
  - GET /api/tags: Get all tags.
  - GET /api/tags/:id: Get a single tag by id.
  - POST /api/tags: Create a new tag.
  - PUT /api/tags/:id: Update a tag by id.
  - DELETE /api/tags/:id: Delete a tag by id.

## Walkthough Video

Please see my [tutorial video](https://drive.google.com/file/d/11a9wvddQGxIbNFBunRSID-nIawZ1ZDvw/view?usp=sharing) for a visual demonstration of the application's functionality.

## License

Licensed under the [MIT](https://opensource.org/licenses/MIT) license.

## Contributing

Contributions to Ivory E-Commerce Back End are welcomed and appreciated! If you encounter bugs, please report them via GitHub issues, providing detailed steps to reproduce. For suggestions or feature enhancements, open an issue to discuss ideas. When contributing code, fork the repository, create a new branch, and submit a pull request to the main branch. Ensure your changes adhere to project coding style and conventions. Please follow the project's Code of Conduct, and note that all contributions are licensed under the MIT License. Thank you for your contributions!

## Questions

Please reach out to me with any questions about this project via:

- [GitHub](https://github.com/IvoryRines)

- [Email](replays_flyers_0q@icloud.com)
