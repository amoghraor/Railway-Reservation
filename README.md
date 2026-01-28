# Railway Reservation Management System

A simple **Railway Management System** web application built using **PHP, HTML, CSS, and MySQL** as a course/demonstration project.  
This project demonstrates user and admin functionality for managing train schedules, bookings, user accounts, cancellations, and station management.

---

## Table of Contents

- [ Overview](#-overview)  
- [ Features](#-features)  
- [ Built With](#built-with)  
- [ Installation](#-installation)  
- [ Project Structure](#-project-structure)  
- [ Usage](#-usage)  


---

## Overview

This project implements a **Railway Reservation System** with the following capabilities:

- Admin login and dashboard  
- Add, edit, delete stations  
- Insert train schedules and class seat information  
- User login and ticket booking  
- View booked tickets & cancellations  
- Search train schedule and user details

The database schema and seed script (railway.sql) are included in the repository.

---

## Features

✔ Admin panel for managing users and train data  
✔ Dynamic train enquiry and schedule display  
✔ User authentication (login/signup forms)  
✔ Ticket booking, cancellation & record views  
✔ MySQL database backend for data storage

---

## Built With

This project uses:

- **PHP** — Core backend scripting  
- **HTML & CSS** — Frontend UI  
- **MySQL** — Database engine  
- **XAMPP / WAMP / LAMP** — Local server environment

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/amoghraor/Railway-Reservation.git
   
## Project Structure

Railway-Reservation/
├── admin_login.php
├── booked.php
├── cancel.php
├── db.php
├── enquiry.php
├── index.htm
├── schedule.php
├── show_trains.php
├── style.css
├── railway.sql

## Usage

- Admin logs in via Admin Login page
- Admin can:
-- Add or remove trains
-- Edit station details
-- View user bookings
- User can:
-- Login or signup
-- Search trains
-- Book or cancel tickets
