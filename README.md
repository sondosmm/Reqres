# Reqres API Postman Testing

## Introduction

Welcome to the Reqres API Postman Collection repository. This collection contains a set of API requests designed to test various endpoints provided by the Reqres API. Reqres is a hosted REST-API service for testing and prototyping, offering functionalities to simulate user management and data manipulation scenarios.

## Getting Started

To begin using this Postman collection for testing the Reqres API:

1. **Clone the Repository**:
   - Clone this repository to your local machine using Git.

2. **Import into Postman**:
   - Open Postman.
   - Click on **Import** to upload the `reqres.postman_collection.json` file, included in this repository, as a collection.

3. **Run Tests**:
   - Execute requests from the imported collection.
   - Review and verify the test results within Postman's test runner.

## Collection Overview

The Reqres API Postman Collection includes the following requests:

- **List Users**: Retrieves a list of users.
- **Single User**: Retrieves details of a single user by ID.
- **Create User**: Adds a new user.
- **Update User**: Updates details of an existing user.
- **Delete User**: Deletes a user.
- **Register**: Registers a new user.
- **Login**: Logs in a user and retrieves a token.
- **Delayed Response**: Demonstrates a delayed response example.
- **List Resources**: Retrieves a list of resources.
- **Single Resource**: Retrieves details of a single resource by ID.
- **Create Resource**: Adds a new resource.
- **Update Resource**: Updates details of an existing resource.
- **Delete Resource**: Deletes a resource.

## Tests

Each request in this collection includes automated tests to verify expected behaviors:

- **Response Status**: Checks the HTTP response status code (e.g., 200 OK, 201 Created).
- **Response Body**: Verifies the structure and content of the JSON response.
- **Data Integrity**: Ensures data sent and received is accurate and consistent.
- **Performance**: Evaluates response times to ensure they meet performance requirements.

