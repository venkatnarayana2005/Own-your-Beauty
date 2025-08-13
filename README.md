# Own your Beauty Services API

A Node.js + Express + MongoDB backend for managing beauty and wellness service bookings, accounts, reviews, and more.

## Features

- **User Account Management** – Register, login, and manage customer profiles
- **Admin Controls** – Manage services, bookings, and customer data
- **Booking System** – Create, update, and view service bookings
- **Contact Form API** – Store and manage customer inquiries
- **Reviews API** – Allow customers to submit and view service reviews
- **Service Listings** – Manage and retrieve available services

## Tech Stack

- **Backend Framework:** [Express.js](https://expressjs.com/)
- **Database:** [MongoDB](https://www.mongodb.com/) with [Mongoose](https://mongoosejs.com/)
- **Runtime:** [Node.js](https://nodejs.org/)
- **Development Tools:** [Nodemon](https://nodemon.io/), CORS

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ownbeauty.git
   cd ownbeauty/MST
npm install
## Set up environment variables:
MONGO_URI=your_mongodb_connection_string
PORT=5000
## Start the development server
npm start

## API Structure
/account – Account management

/admin – Admin operations

/bookings – Booking management

/contactus – Contact form submissions

/reviews – Customer reviews

/services – Service listings

## Project Structure
MST/
 ├── controllers/      # Route logic
 ├── database.js       # MongoDB connection
 ├── index.js          # Entry point
 ├── package.json      # Dependencies & scripts
 └── ...


---

