# Testing a REST API in Node JS with Express using Mocha and Chai


This repository serves as a Mocha testing project for experimenting with Node.js, Express.js, and basic API development principles. The application offers CRUD (Create, Read, Update, Delete) operations for managing tasks, with tasks stored in an in-memory array.

## Table of Contents

- [Overview](#overview)
- [API Endpoints](#api-endpoints)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Running Tests](#running-tests)


## Overview

The main purpose of this project is to provide a testing ground for practicing and experimenting with Mocha, Chai, Node.js, Express.js, and basic API development principles.

## API Endpoints

1. **GET /api/tasks**
   - Retrieves all tasks.

2. **GET /api/tasks/:id**
   - Retrieves a task by its ID.

3. **POST /api/tasks**
   - Creates a new task.

4. **PUT /api/tasks/:id**
   - Updates an existing task.

5. **PATCH /api/tasks/:id**
   - Partially updates an existing task.

6. **DELETE /api/tasks/:id**
   - Deletes an existing task.

## Getting Started

### Prerequisites

- Node.js and npm installed on your machine.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/pankajsh5/mocha-testing.git

2. Change to the project directory:

   ```bash
   cd mocha-testing
3.Install dependencies:

  ```bash
   npm install
```

## Usage

1. Experiment with and modify the source code in the index.js file to test different scenarios.

2. Start the server:
    ```bash
     npm start

The server will start, and you can access the API at http://localhost:3000.


## Running Tests

To run tests using Mocha and Chai, use the following command:


```bash
   npm test
```
This will execute the defined tests in the test directory.



 ```bash
  
Copy and paste this content into a new `README.md` file in your repository. Adjust it further based on your preferences or any additional information you want to include.



