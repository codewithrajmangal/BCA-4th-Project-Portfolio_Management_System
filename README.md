# Portfolio Management System

## Overview
The **Portfolio Management System** is a web-based application developed as a **4th-semester project** using **Laravel 10**. It enables users to track stocks, monitor real-time prices, and manage their investment portfolios efficiently. The project demonstrates fundamental web development skills, including authentication, database management, and dynamic data handling.

## Features
- User registration and secure login
- Add, edit, and delete stocks in the portfolio
- Track real-time stock prices
- Calculate profit and loss for investments
- Dashboard for a quick overview of portfolio performance

## Technologies Used
- **Backend:** Laravel 10 (PHP Framework)  
- **Frontend:** HTML, CSS, Bootstrap  
- **Database:** MySQL  
- **Others:** Composer for dependency management, npm for frontend assets

## Installation

1. **Clone the repository:**
   ```bash
 git clone https://github.com/rajmangalbaitha/portfolio-management-system.git
cd portfolio-management-system

Install dependencies:

bash
Copy code
composer install
npm install
npm run dev
Setup environment:

Copy .env.example to .env

Update database credentials in .env

bash
Copy code
php artisan key:generate
php artisan migrate
Run the application:

bash
Copy code
php artisan serve
Visit http://127.0.0.1:8000 in your browser.

Usage
Register a new account or login with existing credentials

Add stocks to your portfolio and input purchase details

Monitor current stock prices and track profit/loss

Edit or remove stocks as needed

Contribution
This project is primarily for learning purposes. Contributions are welcome to improve features or optimize the code.

License
