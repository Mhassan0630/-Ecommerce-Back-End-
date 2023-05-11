# E-commerce Back End Starter Code


This is a simple E-commerce back-end API built with Node.js, Express, and Sequelize ORM. The API supports CRUD operations for products, categories, and tags in an e-commerce application.

## Getting Started

These instructions will help you set up the project on your local machine for development and testing purposes.

### Prerequisites

- [Node.js](https://nodejs.org/) (v14.x or higher)
- [MySQL](https://www.mysql.com/) server

### Installation

1. Clone the repository to your local machine:
2. Install the required dependencies:
3. Create a `.env` file in the root directory and add the following environment variables:
4. Start your MySQL server and create the `ecommerce_db` database:
5. Run the database migrations and seed the database with sample data:
6. Start the server:

## API Endpoints

The API provides the following endpoints for interacting with the data:

### Products

- `GET /api/products` - Retrieve all products
- `GET /api/products/:id` - Retrieve a single product by ID
- `POST /api/products` - Create a new product
- `PUT /api/products/:id` - Update an existing product
- `DELETE /api/products/:id` - Delete a product

### Categories

- `GET /api/categories` - Retrieve all categories
- `GET /api/categories/:id` - Retrieve a single category by ID
- `POST /api/categories` - Create a new category
- `PUT /api/categories/:id` - Update an existing category
- `DELETE /api/categories/:id` - Delete a category

### Tags

- `GET /api/tags` - Retrieve all tags
- `GET /api/tags/:id` - Retrieve a single tag by ID
- `POST /api/tags` - Create a new tag
- `PUT /api/tags/:id` - Update an existing tag
- `DELETE /api/tags/:id` - Delete a tag

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to the project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.









