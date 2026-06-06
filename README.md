# Parking Management System API

## Overview

The Parking Management System API is a backend application developed using Java, Spring Boot, Maven, and MySQL. The project follows a microservices-based architecture and provides REST APIs for managing parking operations.

The system is designed to handle vehicle parking activities, parking slot management, guard management, payment management, and report generation through role-based access control.

Users are authenticated through a session-based login system, and access to functionalities is granted based on their assigned roles.

---

## Features

### Authentication & Session Management

* User Login
* User Logout
* Session-Based Authentication
* Role-Based Access Control

### Admin Module

* Add New Guards
* Update Guard Information
* Delete Guards
* Manage Parking Slots
* View Vehicle Parking Records
* Manage Payment Details
* Generate Reports
* Monitor Parking Activities

### Guard Module

* Add Vehicle Entry
* Allocate Parking Slots
* Manage Vehicle Exit
* Generate Parking Reports
* View Parking Information

### Vehicle Management

* Vehicle Registration
* Vehicle Entry Tracking
* Vehicle Exit Tracking
* Parking Slot Assignment
* Vehicle Parking History

### Parking Slot Management

* Create Parking Slots
* Update Parking Slot Status
* Monitor Slot Availability
* Manage Slot Allocation

### Payment Management

* Store Payment Records
* View Payment Details
* Manage Parking Charges

### Report Generation

* Vehicle Reports
* Parking Reports
* Payment Reports

---

## Architecture

The application follows a Microservices Architecture where different modules are separated into independent services to improve maintainability and scalability.

### Services

* Parking Management Service
* Guard Management Service
* Vehicle Management Service
* Payment Management Service

---

## Technology Stack

* Java
* Spring Boot
* Spring Data JPA
* Hibernate
* REST APIs
* Maven
* MySQL
* Microservices Architecture

---

## Project Structure

* Controller Layer
* Service Layer
* Repository Layer
* Entity Layer
* DTO Layer
* REST API Endpoints
* Database Integration using MySQL

---

## Key Highlights

* RESTful API Development
* Session-Based Authentication
* Role-Based Access Control
* Microservices-Based Design
* Database Integration with MySQL
* Layered Architecture
* Parking Slot Management
* Vehicle Tracking System

---

## API Modules

### Authentication API

Handles user authentication and session management.

### Vehicle API

Manages vehicle entry, exit, and parking information.

### Guard API

Handles guard-related operations and management.

### Parking API

Manages parking slots and parking activities.

### Payment API

Handles parking payment records.

### Report API

Generates parking and vehicle reports.

---

## Author

**Mayur Hipparkar**

Java Developer | Spring Boot Developer

