# Tay’s Gourmets Case Study

## Project Type

Full stack e-commerce platform

## Summary

Tay’s Gourmets is a full stack e-commerce platform built to support online product browsing, customer accounts, secure checkout, payment processing, and rewards-based purchasing.

The project was built with a MERN-style stack using React, Node, Express, MongoDB, Mongoose, TypeScript, and Stripe.

This case study focuses on the technical and product work involved in building a real business system, not just a static website.

## Problem

The business needed more than a basic marketing site. It needed a working e-commerce system that could support customer purchases, account-based features, payment processing, and a rewards experience tied to customer activity.

The key challenge was building a system that connected the customer-facing experience with the back-end business logic needed for orders, accounts, points, and checkout.

## Goals

The project needed to support:

- Product browsing
- Customer account creation
- Customer login and account-based functionality
- Secure checkout
- Stripe payment processing
- Purchase-based points
- Rewards redemption during checkout
- Database-backed customer and order data
- A maintainable full stack architecture

## Technology Stack

### Front End

- React
- TypeScript
- JavaScript
- HTML
- CSS

### Back End

- Node.js
- Express.js
- TypeScript

### Database

- MongoDB
- Mongoose

### Payments

- Stripe

### Development and Deployment Areas

- API development
- Environment configuration
- Secure payment flow handling
- Production deployment considerations
- Account and checkout flow testing

## Key Features

## Customer Accounts

The platform supports customer account creation and account-based functionality. This creates the foundation for repeat customer activity, order tracking, rewards logic, and personalized checkout behavior.

## Stripe Payment Processing

Stripe was integrated to support secure payment processing. The checkout flow needed to connect front-end customer actions with back-end payment and order logic.

Key considerations included:

- Creating a reliable checkout flow
- Passing correct order and customer information
- Handling payment-related edge cases
- Keeping sensitive payment handling separated from normal application logic
- Supporting a smooth customer experience through checkout

## Purchase-Based Points

The platform includes a points system where customers can earn points through purchases.

This required the application to connect:

- Customer accounts
- Completed purchases
- Database updates
- Rewards balances
- Checkout logic

## Rewards Redemption at Checkout

Customers can use earned points during checkout. This required the checkout flow to account for rewards before finalizing the transaction.

Important considerations included:

- Verifying the customer’s available points
- Applying points correctly during checkout
- Preventing incorrect reward usage
- Updating points after purchase completion
- Keeping the customer experience simple

## Database-Backed Application Logic

The project uses MongoDB and Mongoose to support structured application data.

Core database areas include:

- Customers
- Products
- Orders
- Rewards or points-related data
- Account-related data

## API-Driven Architecture

The back end uses Node and Express to support API routes that connect the front end, database, payment logic, and customer account behavior.

The API layer supports the core business logic behind the application instead of relying only on front-end behavior.

## Technical Challenges

## Connecting E-Commerce Logic Across the Stack

One of the main challenges was making sure the front end, API, database, account system, rewards system, and payment flow worked together correctly.

E-commerce applications require careful coordination because customer-facing actions often trigger several back-end changes.

For example:

- A customer adds products to checkout
- The system calculates totals
- Available rewards may need to be checked
- Stripe payment processing happens
- The order must be saved
- Customer points may need to be updated
- Account data must remain accurate

## Handling Payment and Rewards Edge Cases

The project required thinking through edge cases around checkout and customer rewards.

Examples include:

- What happens if a customer tries to use more points than they have
- What happens if payment succeeds but a follow-up database update fails
- What happens if a customer is logged in versus not logged in
- How customer points should be calculated after purchase
- How rewards affect the final checkout amount

## Building for a Real Business Use Case

This was not just a portfolio mockup. The project needed to support a real business selling real products.

That meant the system needed to be practical, understandable, and maintainable.

## Product Thinking

This project required thinking beyond individual features.

Important product considerations included:

- Making checkout easy for customers
- Giving customers a reason to return through points and rewards
- Making account creation valuable
- Keeping the e-commerce flow understandable
- Supporting future business growth
- Creating a foundation for additional customer features later

## What I Built

My work included:

- Building the React front end
- Building the Node and Express back end
- Creating API routes for application functionality
- Working with MongoDB and Mongoose models
- Integrating Stripe payment processing
- Implementing customer account functionality
- Implementing purchase-based points
- Implementing checkout rewards redemption
- Connecting front-end actions to back-end business logic
- Testing account, checkout, and rewards behavior
- Supporting deployment and production readiness concerns

## What This Project Demonstrates

This project demonstrates my ability to build a real full stack business application.

It shows experience with:

- Full stack web development
- E-commerce architecture
- Payment integration
- Customer account systems
- API development
- Database-backed application logic
- Rewards and points systems
- Business-focused software development
- Turning a business need into a working product

## What I Would Improve Next

Future improvements could include:

- Better admin tools for managing products and orders
- More detailed customer order history
- Improved analytics around purchases and rewards
- More automated testing for checkout and rewards logic
- Improved deployment automation
- Better email notifications for account and order activity
- More detailed security review around account and checkout flows
- Stronger reporting tools for business operations

## Main Takeaway

Tay’s Gourmets shows that I can build more than a basic website. I can build a full stack business system with accounts, payments, database-backed logic, customer rewards, API functionality, and real e-commerce behavior.
