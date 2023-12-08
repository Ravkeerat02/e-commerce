# E-Commerce App using Payload CMS

## Setup

### Prerequisites
Ensure you have Node.js and npm installed on your machine.

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/Ravkeerat02/e-commerce
    ```

2. Remove existing `node_modules`:

    ```bash
    rm -rf node_modules
    ```

3. Install dependencies:

    ```bash
    npm install --legacy-peer-deps
    ```

## Working with Database

### GraphQL Schema Generation

To work with the Payload CMS database, follow these steps:

1. Generate GraphQL Schema:

    ```bash
    yarn payload generate:graphQLSchema
    ```

2. Generate TypeScript types:

    ```bash
    yarn generate:types
    ```

## Technologies Used

### Language

- TypeScript

### Frameworks and Libraries

- SCSS
- Payload CMS
- GraphQL

## Folder Structure

Explain the key folders and their purposes:

- `src/`: Contains the source code.
- `public/`: Public assets like images, icons, etc.
- `payload/`: Configuration files for Payload CMS.

## Scripts

List important npm scripts:

- `npm start`: Start the development server.
- `npm run build`: Build the production-ready app.
- `npm run lint`: Run linting checks.

## Features 

To be added 
