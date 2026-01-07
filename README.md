# Mini Store – Ruby on Rails

Mini Store is a simple Ruby on Rails project built to understand and demonstrate core Rails concepts such as authentication, associations, CRUD operations, and validations.

This project focuses on backend fundamentals, not UI or advanced features.

## ✨ Features

- User Signup
- User Login & Logout (Session-based authentication)
- Secure password storage using bcrypt
- Product management (Create, Read, Update, Delete)
- User–Product association
- Validations and authorization

## 🛠 Tech Stack

- Ruby on Rails
- SQLite (development)
- ERB (HTML templates)
- bcrypt (password encryption)

## 🔐 Authentication

- Users sign up using email and password
- Passwords are encrypted using `has_secure_password`
- Login creates a session
- Logout destroys the session
- No external authentication gems (like Devise) were used

## 🔗 Associations

- User has many products
- Product belongs to a user
- Each user can only view and manage their own products

## ▶️ Run Locally

```bash
bundle install
rails db:migrate
rails server

