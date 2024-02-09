# E Store Warehouse

## Description

This project is an online store application built with React for the frontend and Node.js with Express for the backend. It allows users to browse, search, and purchase products, manage their shopping cart, and interact with the store's features.

## Table of Contents

  1. [Installation](#Installation)
  2. [Usage](#Usage)
  3. [API Endpoints](#API-Endpoints)
  4. [Project Video](#Project-Video)

## Installation

To install and run the application locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/SyedSabee/E-Store-Warehouse
2. Navigate to the project directory:
   ```bash
   cd online-store
3. Install dependencies:
   ```bash
   npm install
4. Start the backend server and Frontend together:
   ```bash
   npm run dev
Access the application at `http://localhost:5173` in your browser.

## Usage
Once the application is running, users can:

  - Browse products by category or search for specific items.
  - View product details, including images, descriptions, and prices.
  - Add products to their shopping cart and adjust quantities.
  - Proceed to checkout and enter shipping and payment information.
  - Register and log in to manage their account and view order history.

## API-Endpoints

### Users
  - **POST /api/users/auth**
      - Description: Authenticate a user.
      - Request Body: { "email": "example@example.com", "password": "password" }
      - Response: { "token": "JWT_TOKEN" }

### Categories
  - **POST /api/category**
      - Description: Create a new category.
      - Request Body: `{ "name": "Category Name" }`
      - Response: `{ "id": "CATEGORY_ID", "name": "Category Name" }`

... (continue listing all API endpoints)


# Project-Video

https://github.com/SyedSabee/E-Store-Warehouse/assets/145167243/26174733-ce66-4386-89c6-c26284c8ae25
