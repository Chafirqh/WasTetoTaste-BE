# Auth
Login Register 
This repository contains the backend implementation for user authentication using Express.js and MySQL on Google Cloud SQL.

# Table of Contents
Overview
Prerequisites
Installation
Configuration
Usage
API Endpoints
Security
Contributing
License

# Overview
This backend service provides endpoints for user registration and login using Express.js and MySQL database hosted on Google Cloud SQL. It securely handles user authentication and manages user data in the MySQL database.
# Prerequisites
Node.js (version 12.x or higher)
Express.js
MySQL (or Cloud SQL for MySQL on Google Cloud Platform)
Google Cloud SDK (for deploying to GCP)
# Installation
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/auth-backend.git
cd auth-backend
Install dependencies:

bash
Copy code
npm install
Configuration
Set up Google Cloud SQL:

Create a MySQL instance on Google Cloud SQL.
Ensure your instance allows external connections if accessing from outside Google Cloud.
Environment variables:

Create a .env file in the root directory and add/edit the following environment variables as per your setup:
