# PG Life

PG Life is a PHP-based property rental web application that helps users discover paying-guest accommodations by city, view property details, and manage properties they are interested in.

## Features

- Browse PG properties by city
- View property details and amenities
- Search and explore available listings
- User registration and login
- Interested properties dashboard
- React-based UI companion app for the property listing experience

## Tech Stack

- PHP
- MySQL
- HTML, CSS, and JavaScript
- Bootstrap
- React (inside the react-app folder)

## Project Structure

- index.php - Home page
- property_list.php - Listing page for properties
- property_detail.php - Detailed view of a property
- dashboard.php - User dashboard
- api/ - PHP endpoints for login, signup, and property actions
- includes/ - Shared PHP includes such as header, footer, and database connection
- css/ - Stylesheets
- js/ - Front-end JavaScript
- react-app/ - React application for the listing UI

## Prerequisites

- XAMPP, WAMP, or MAMP installed
- Apache and MySQL running
- Node.js and npm (for the React app)

## Installation

1. Place the project folder in your web server root:
   - XAMPP: C:\xampp\htdocs\pglife

2. Start Apache and MySQL from your local server control panel.

3. Create a MySQL database named pglife.

4. Update the database credentials if needed in includes/database_connect.php.

5. Open the project in your browser:
   - https://pglifeproject.byethost7.com/

## React App Setup

If you want to run the React-based UI inside the react-app folder:

```bash
cd react-app
npm install
npm start
```

## Notes

- The project currently expects a MySQL database connection using the pglife database.
- If you have a SQL dump for the project, import it into the database before testing the app.
- If your MySQL port is different from the default, update the connection settings in includes/database_connect.php.

## License

This project is for educational and personal use.
