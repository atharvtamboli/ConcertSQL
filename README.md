# ConcertDB

A full-stack concert ticket management system built around a relational MySQL database. The application provides a web interface for event discovery, ticket booking, user management, reviews, venue management, and database analytics.

## Overview

ConcertDB demonstrates the design and implementation of a relational database-backed application using MySQL and a Node.js/Express.js backend.

The system handles the complete ticket booking workflow, including event availability, bookings, ticket generation, payments, reviews, and revenue analysis.

## Tech Stack

### Backend
- Node.js
- Express.js
- MySQL2

### Database
- MySQL
- Relational Database Design
- SQL Joins
- Aggregate Queries
- Stored Procedures
- SQL Functions
- Cursors
- Triggers

### Frontend
- HTML5
- CSS3
- JavaScript
- REST API integration

## Core Features

- Event discovery and search
- Event details and schedules
- User management
- Ticket booking
- Automatic ticket availability updates
- Payment record management
- Event reviews and ratings
- Venue and staff management
- Revenue and booking analytics
- Database-driven SQL operations

## Database Implementation

The project uses a relational MySQL database consisting of entities such as:

- Users
- Events
- Venues
- Organizers
- Staff
- Bookings
- Tickets
- Payments
- Reviews
- Event Schedules
- Seat Categories

The application demonstrates multiple database programming concepts including:

- Primary and foreign key relationships
- Multi-table joins
- Aggregation and grouping
- Stored procedures
- User-defined functions
- Cursors
- Triggers
- Transaction-based booking operations

## SQL Lab

The application includes an interactive SQL Lab for demonstrating database programming concepts.

It provides interfaces for:

- SQL Functions
- Stored Procedures
- Cursors
- Triggers

Results are retrieved from MySQL through REST API endpoints and displayed directly in the application.

## Project Structure

ConcertDB/
├── index.html
├── server.js
├── database.sql
├── package.json
├── package-lock.json
├── .gitignore
└── README.md

## Setup
1. Clone the Repository
git clone https://github.com/atharvtamboli/ConcertSQL.git
cd ConcertDB
2. Install Dependencies
npm install
3. Configure MySQL

Create the database and import the provided SQL file:

SOURCE database.sql;

Ensure the MySQL server is running and configure the database connection in the backend.

4. Start the Server
node server.js
