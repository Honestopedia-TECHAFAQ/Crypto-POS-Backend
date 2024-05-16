
**Developed by Afaq Ahmad**

## Overview

Welcome to the Node.js framework TypeScript starter repository. This boilerplate provides a solid foundation for building Node.js applications with essential functionalities pre-implemented. It includes user authentication, database operations, email sending capabilities, and integration with payment gateways such as Stripe and Paypal. Additionally, it offers features like currency conversion through Rapid API and crypto-to-fiat conversion via Kraken.

## Features

* **User Authentication** : Includes login and signup routes with data storage in MongoDB using Mongoose.
* **CRUD Operations** : Basic CRUD function routes utilizing MongoDB.
* **Email Sending** : Integrated with Nodemailer for sending emails.
* **Payment Methods** : Supports Stripe and Paypal payment gateways.
* **Currency Conversion** : Utilizes Rapid API for currency conversion.
* **Crypto-to-Fiat Conversion** : Implements Kraken for crypto-to-fiat conversion.

## Configuration

Before running the application, ensure the following keys are updated:

* **JWT Secret Key** : Update the secret key in the `.env` file for token encryption and generation.
* **Mongoose Private Key** : Update the private key in the `config.json` file.
* **Stripe Secret Key** : Update the secret key in the `.env` file for Stripe integration.
* **Sender Email Credentials** : Update the email and password for the sender email.
* **Paypal Secrets** : Update the keys in the Paypal services file.
* **Rapid API and Kraken Keys** : Update the keys in their respective service files.

## Installation

$ npm install



## Running the Application

To run the application:



# Development mode

$ npm run start

# Watch mode

$ npm run start:dev

# Production mode

$ npm run start:prod



## Testing

To run tests:



# Unit tests

$ npm run test

# End-to-end tests

$ npm run test:e2e

# Test coverage

$ npm run test:cov
