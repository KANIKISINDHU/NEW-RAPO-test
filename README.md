Candidate Management Application

A web application built with React.js, Node.js, and MySQL to display, search, filter, and manage candidates' data.

Table of Contents
- #getting-started
- #prerequisites
- #installation
- #running-the-application
- #features
- #technologies-used

Getting Started
To get started with the application, follow the instructions below.

Prerequisites
- Node.js (version 14 or higher)
- MySQL (version 5.7 or higher)
- npm (version 6 or higher)

Installation
1. Clone the repository: git clone https://github.com/username/candidate-management-app.git
2. Install dependencies: npm install
3. Create a MySQL database and update the database credentials in server/config/db.js
4. Run the database schema: mysql -u username -p database_name < server/schema.sql

Running the Application
1. Start the server: npm start
2. Open the application in your browser: http://localhost:3000

Features
- Display candidates in a table format
- Search candidates by name, phone, or email
- Filter candidates by experience, gender, and skills
- Add new candidates
- Pagination for large datasets

Technologies Used
 React.js for the frontend
- Node.js for the backend
- MySQL for the database
- Express.js for API routing
