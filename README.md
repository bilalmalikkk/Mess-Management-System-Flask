
# Mess Management System in Flask

![Mess Management System](/static/img/logo.png)

The Mess Management System is a web application built using Flask, a Python web framework, to manage mess-related tasks and activities efficiently.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The Mess Management System is designed to streamline the operations of a mess by providing tools for administrators and students to manage various tasks such as menu updates, payments, attendance, and more. The system offers a user-friendly interface for both administrators and students.

## Features

- **User Authentication**: Secure login and registration system for both administrators and students.
- **Role-based Access**: Different functionalities are accessible based on user roles (admin/student).
- **Menu Management**: Admins can update daily menus for breakfast, lunch, and dinner.
- **Payment Integration**: Seamless integration with Stripe API for handling online payments.
- **Attendance Tracking**: Admins can manage attendance records for students.
- **Analytics**: Students can view their meal consumption analytics.
- **Polls**: Interactive polls for users to participate in and provide feedback.
- **Profile Management**: Users can view and update their profiles.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/bilalmalikkk/Mess-Management-System-Flask.git
   cd Mess-Management-System-Flask
   ```

2. Install required packages using pip (Python package manager):
   ```bash
   pip install -r requirements.txt
   ```

3. Set up the database:
   - MongoDB is used as the database. Make sure you have MongoDB installed and running.
   - Update the `dbUrl` in `app.py` with your MongoDB connection URL.

4. Configure Stripe API:
   - Replace `"sk_test_XXXXXXXXXXXXXXXXXXXXXXXX"` with your Stripe API key in `app.py`.

5. Run the application:
   ```bash
   python app.py
   ```

## Usage

1. Access the application in your web browser at `http://127.0.0.1:5000`.
2. Login using your credentials as an admin or student.
3. Navigate through the different sections of the application based on your role.

## Technologies Used

- Flask (Python Web Framework)
- MongoDB (Database)
- Stripe API (Payment Integration)
- HTML/CSS (Frontend)
- JavaScript (Frontend Interactivity)

