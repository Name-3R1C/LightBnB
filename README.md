# LightBnB

This project is to design a database and use server-side JavaScript to display the information from queries to web pages.

# Description
LightBnB is a web application that utilizes a database and server-side JavaScript to display information from queries on web pages. It provides a platform for users to search for and book rental properties. Property owners can also list their properties for others to browse and book.

# Installation

1. Clone the repository:

```
git clone https://github.com/Name-3R1C/LightBnB.git
```
2. Install dependencies:
```shell
npm install
```

# Usage
1. Ensure database is set up (see Database section for details)
2. Run the server:
```
npm run local
```
3. Open a web browser and navigate to http://localhost:3000 to access LightBnB.


# Database
LightBnB uses a PostgreSQL database to store property and user information. To set up the database, follow these steps:
1. Install PostgreSQL (if not already installed).
2. Create a new PostgreSQL database called `lightbnb`
```
CREATE DATABASE lightbnb;
```
3. Navigate to the database:
```
\c lightbnb
```
4. create the necessary tables and populate them with sample data:
```
\i migrations/01_schema.sql
\i seeds/01_seeds.sql
\i seeds/02_seeds.sql
```

# Dependencies
- bcrypt
- cookie-session
- express"
- nodemon"
- pg