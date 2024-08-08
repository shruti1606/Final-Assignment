# Online Bookstore
## Project Overview
In this project, we are designing an online bookstore that offers physical books, e-books, and audiobooks. The primary objective is to create a robust database and application infrastructure that supports various functionalities including browsing catalogs, making purchases, and posting reviews. The system will integrate data related to customers, authors, publishers, books, and sales. The aim is to deliver a user-friendly and efficient system that enhances the browsing and purchasing experience.
## Roles of Group Members:
Name | Role
--- | :---
Shruti Patel | Database & Tables Creation, RESTful API
Pratham Parekh | CRUD Operations
Vansh Palkhiwala | Interface Implementation, Unit Testing
## Getting Started

### Prerequisites

We have the following installed on our virtual machine:

- [Node.js](https://nodejs.org/) (including npm)
- MVC Model

### Starting Development

1. We installed Node and NPM by running the following commands:

    ```bash
    node -v
    npm -v
    ```

    Ensuring the version numbers.

2. We Installed the required dependencies using these commands:

    ```bash
    npm install
    ```

    To install the npm package:

    ```bash
    npm install typeorm --save
    ```

    To install reflect-metadata shim:

    ```bash
    npm install reflect-metadata --save
    ```

    then import it:
   
    ```typescript
    import "reflect-metadata"
    ```

    To install node typings:

    ```bash
    npm install @types/node --save-dev
    ```

4. Start the development environment:

    ```bash
    npm start
    ```

### Tests

Run tests with:


npm run test
