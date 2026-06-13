# PH-Assignment-3: Football Ticket Booking System Database

## Description

This assignment implements a relational database for a **Football Ticket Booking System**. It includes the design and creation of three interconnected tables (Users, Matches, and Bookings) with appropriate constraints, relationships, and sample data.

## Database Schema Overview

### Tables

- **Users**: Stores user information including full name, email, role (Ticket Manager or Football Fan), and phone number
- **Matches**: Contains match details such as fixture, tournament category, base ticket price, and match status
- **Bookings**: Records ticket bookings with references to users and matches, including seat number, payment status, and total cost

### Key Features

- Foreign key relationships between tables for data integrity
- CHECK constraints to enforce valid data values
- Sample data populated for testing and demonstration
- Support for multiple roles and booking statuses

## Files

- `QUERY.sql` - SQL script containing table creation and sample data insertion
