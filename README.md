# JomBus - Bus Booking System

A modern web-based bus booking application built with **PHP** and **MySQL**. JomBus provides a seamless platform for users to search for bus trips, make reservations, manage bookings, and process payments online.

## Features

- **User Authentication** - Secure signup and login system
- **Trip Search** - Browse and filter available bus routes
- **Booking Management** - Create, view, and manage reservations
- **Seat Selection** - Interactive seat selection interface
- **Payment Processing** - Handle online payments
- **User Profile** - Manage personal information and preferences
- **Receipt Generation** - Generate and view booking receipts
- **Responsive Design** - Optimized for all devices

## Tech Stack

- **Backend**: PHP 7.2+
- **Database**: MySQL 5.7+
- **Frontend**: HTML5, CSS3
- **Server**: Apache/Nginx

## Project Structure

```
JomBus/
├── public/                      # Web root (set as server document root)
│   ├── index.php               # Entry point
│   ├── *.php                   # Page and process files
│   ├── css/
│   │   └── Style.css           # Stylesheet
│   └── images/                 # Image assets
│
├── src/
│   └── config/
│       ├── db_connection.php   # Database configuration
│       └── session.php         # Session management
│
├── database/
│   └── create_database.sql     # Database schema
│
├── .gitignore                  # Git ignore configuration
├── LICENSE                     # MIT License
└── README.md                   # This file
```

## Quick Start

### Prerequisites
- PHP 7.2 or higher
- MySQL 5.7 or higher
- Apache/Nginx web server
- Composer (optional)

## How It Works

1. **Sign Up/Login** - Create an account or login with existing credentials
2. **Search** - Browse available bus trips by route and date
3. **Select Seats** - Choose your preferred seats interactively
4. **Checkout** - Review booking details
5. **Pay** - Process payment online
6. **Confirm** - Receive instant booking confirmation and receipt
7. **Manage** - View and modify bookings in "My Bookings"