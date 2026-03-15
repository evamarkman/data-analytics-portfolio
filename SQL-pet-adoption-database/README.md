# Pet Adoption Database (SQL Project)

This project demonstrates the design of a relational database for a pet adoption system.

## Database Structure

The database contains three main tables:

Adopter
Pet
Adoption

Relationships:
- Each adopter can adopt multiple pets
- Each pet adoption is recorded in the Adoption table
- Adoption connects Adopter and Pet using foreign keys

## Tables

Adopter
- adopterID (Primary Key)
- name
- phoneNumber
- address

Pet
- petID (Primary Key)
- name
- species

Adoption
- adoptionID (Primary Key)
- adopterID (Foreign Key)
- petID (Foreign Key)
- fee
- adoptionDate

## Features

- relational schema design
- primary and foreign keys
- structured data insertion
- adoption transaction tracking

## Tools

SQL
Relational Database Design
