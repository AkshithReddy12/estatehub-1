# EstateHub

## Overview

EstateHub is a web-based e-commerce platform designed to connect real estate buyers and sellers. It provides a seamless property discovery experience through an intuitive interface, secure authentication, smart filters, and automated email notifications for real-time updates.

## Features

- *User Authentication*: Secure login and registration using Google Sign-In.
- *Property Listings*: Buyers can browse and filter available properties by type, location, price, and more.
- *Search Filters*: Advanced filter-based search to help users find relevant properties faster.
- *Email Notifications*: Automatic emails sent to users for property inquiries and activity updates.
- *Responsive UI*: Simple and user-friendly interface for desktop and mobile users.

## Technologies Used

- *Frontend*: HTML, CSS, JavaScript, EJS, Bootstrap
- *Backend*: Node.js, Express.js
- *Database*: MongoDB, Mongoose
- *Authentication*: Google OAuth 2.0
- *Email Service*: NodeMailer

## Installation

To set up the project locally, follow these steps:

1. *Clone the repository*:
   ```bash
   git clone https://github.com/AkshithReddy12/estatehub-1
   cd estatehub

2. *Create a .env file in the root directory and add the following variables:*
   ```bash
   CLIENT_ID=        # Google OAuth client ID
   CLIENT_SECRET=    # Google OAuth client secret
3. *Install dependencies*:
   ```bash
   npm install
4. *Run server*:
   ```bash
   node index.js
5. *Go to browser and open*:
    ```bash
    http://localhost:3000/
    
