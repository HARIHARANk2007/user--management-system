# User Management App

A simple web application for managing users built with Node.js, Express.js, and EJS.

## Features

- View a list of users
- Add new users
- Update existing user information
- Delete users

## Installation

1. Clone the repository or download the project files.
2. Navigate to the project directory.
3. Install dependencies:

   ```
   npm install
   ```

## Usage

1. Start the server:

   ```
   node pro.js
   ```

2. Open your browser and go to `http://localhost:3000`.

3. Use the web interface to:
   - View users on the home page
   - Add a new user by filling the form and submitting
   - Update a user by modifying their details and submitting the update form
   - Delete a user by selecting and confirming deletion

## Dependencies

- express: ^5.1.0
- ejs: ^3.1.10
- body-parser: ^2.2.0

## Project Structure

- `pro.js`: Main server file containing routes and logic
- `views/home.ejs`: EJS template for the home page
- `package.json`: Project dependencies and configuration