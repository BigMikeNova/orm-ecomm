# orm-ecomm

# 13 Object-Relational Mapping (ORM): E-Commerce Back End

## GitHub Repository

https://github.com/BigMikeNova/orm-ecomm

## Link to Video Walkthrough

https://www.loom.com/share/b00676c038514be0882157631fe0d6fd

# Project Name

Project Description.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Environment Variables](#environment-variables)
- [Database Setup](#database-setup)
- [API Routes](#api-routes)
- [Testing](#testing)
- [Contributing](#contributing)
- [License](#license)

## Installation

To install and set up the project, follow these steps:

1. Clone the repository.
2. Install the dependencies by running the following command:

   ```shell
   npm install

## Usage

To use the project, follow these steps:

1. Make sure you have set up the required environment variables (see [Environment Variables](#environment-variables) section).
2. Run the following command to start the server:

   ```shell
   npm start
## Environment Variables

The project requires the following environment variables to be set. Create a `.env` file in the root directory and add the following variables:

markdown

## Environment Variables

The project requires the following environment variables to be set. Create a `.env` file in the root directory and add the following variables:

DB_NAME=your_database_name
DB_USER=your_mysql_username
DB_PASSWORD=your_mysql_password


Make sure to replace `your_database_name`, `your_mysql_username`, and `your_mysql_password` with your actual database and MySQL credentials.

## Database Setup

To set up the database, follow these steps:

1. Make sure you have created a MySQL database.
2. Set the required environment variables as described in the [Environment Variables](#environment-variables) section.
3. Run the following command to create and seed the development database:

   ```shell
   npm run seed

The development database will be created and seeded with test data.

## API Routes

The API provides the following routes:

- `GET /api/categories`: Retrieves all categories.
- `GET /api/products`: Retrieves all products.
- `GET /api/tags`: Retrieves all tags.
- `POST /api/categories`: Creates a new category.
- `POST /api/products`: Creates a new product.
- `POST /api/tags`: Creates a new tag.
- `PUT /api/categories/:id`: Updates a category by ID.
- `PUT /api/products/:id`: Updates a product by ID.
- `PUT /api/tags/:id`: Updates a tag by ID.
- `DELETE /api/categories/:id`: Deletes a category by ID.
- `DELETE /api/products/:id`: Deletes a product by ID.
- `DELETE /api/tags/:id`: Deletes a tag by ID.

Make sure to replace `:id` with the actual ID of the resource you want to perform the action on.

## Testing

To test the API routes, you can use a tool like [Insomnia](https://insomnia.rest/) or any other API testing tool.