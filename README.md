# Online-Ticket-Booking-System

## Description:
This is a web-based flight booking system that allows users to search for available flights, book tickets, and make payments online. Users can view their booking history, download e-tickets, and reset their passwords if needed. The system also includes a feedback section where users can provide their experience and suggestions.

## Key Features:
User Registration and Login
Flight Search and Booking
Secure Online Payment Processing
E-ticket Generation
Booking History Management
Password Reset Functionality
User Feedback Submission

## Technology Stack:
Frontend: HTML, CSS, Bootstrap, JavaScript
Backend: PHP
Database: MySQL
Payment Integration: (Specify if using any payment gateway like PayPal, Stripe, etc.)

## Installation:
Clone the Repository:
bash
Copy code

## Configure Database:
Import the flight_booking.sql file into MySQL to create the necessary tables.
Update database connection details in config.php (or wherever your connection setup is).

## Set Up Server:
Place the project files in your web server's root directory (e.g., /var/www/html/ for Apache).
Start your local server (e.g., Apache or XAMPP).

## Configure Payment Gateway:
Set up the payment gateway credentials (if applicable) in the payment.php file.

## Access the Application:
Open a browser and navigate to http://localhost/your-project-name/ to access the system.

## Usage:
User Registration: Users can register by filling out the form on the registration page.
Login: Use the credentials to log in and access the flight booking system.
Book a Flight: Search for flights, select one, enter passenger details, and proceed with payment.
View Bookings: After booking, users can view their flight history and download e-tickets.
Feedback: Users can submit feedback after completing their journey.

## File Structure:
index.php: The homepage for flight search.
register.php: User registration page.
login.php: User login page.
book_flight.php: Page for booking a flight.
payment.php: Payment processing page.
e_ticket.php: E-ticket generation after successful booking.
my_flights.php: Displays the user’s booking history.
feedback.php: Feedback form for users.
reset-pwd.php: Password reset page.
