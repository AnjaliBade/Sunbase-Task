# Sunbase-Task
# Customer CRUD Application

This is a CRUD application for managing customers, built with Spring Boot for the backend and HTML/CSS/JavaScript for the frontend. The application includes JWT authentication and supports operations to create, read, update, and delete customer records. Additionally, it can synchronize customer data with a remote API.

## Technologies Used

- **Backend**: Spring Boot
- **Frontend**: HTML, CSS, JavaScript
- **Database**: MySQL
- **Authentication**: JWT (JSON Web Token)

## Features

- **Create a customer**: Add a new customer to the database.
- **Update a customer**: Edit details of an existing customer.
- **Get a list of customers**: Fetch a paginated, sorted, and searchable list of customers.
- **Get a single customer**: Retrieve details of a specific customer by ID.
- **Delete a customer**: Remove a customer from the database.
- **Authentication**: Secure the API with JWT-based authentication.
- **Sync data**: Synchronize customer data with a remote API.

## Customer Object Structure

```json
{
  "first_name": "Jane",
  "last_name": "Doe",
  "street": "Elvnu Street",
  "address": "H no 2",
  "city": "Delhi",
  "state": "Delhi",
  "email": "sam@gmail.com",
  "phone": "12345678"
}
