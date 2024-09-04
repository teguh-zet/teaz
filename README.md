# Perfume E-commerce Website

## Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Tech Stack](#tech-stack)
4. [Installation and Setup](#installation-and-setup)
5. [Backend Structure](#backend-structure)
6. [Frontend Structure](#frontend-structure)
7. [API Documentation](#api-documentation)
8. [Usage](#usage)
9. [Testing](#testing)
10. [Deployment](#deployment)
11. [Contributing](#contributing)
12. [License](#license)
13. [Contact](#contact)

## Introduction

This project is a fully functional e-commerce website for selling perfumes. It allows users to browse various perfume products, add them to a cart, and complete a purchase. The website also includes authentication features, user profiles, and order history.

## Features

- User authentication and authorization (login, registration, password reset).
- Product catalog with detailed descriptions and images.
- Shopping cart functionality.
- Order management and history tracking.
- Secure payment gateway integration.
- Responsive design compatible with desktop and mobile devices.
- Admin panel for managing products, orders, and users.

## Tech Stack

### Backend
- **Java Spring Boot**: For building the RESTful API.
- **Spring Security**: For managing user authentication and authorization.
- **PostgreSQL**: As the relational database for storing data.
- **JWT (JSON Web Tokens)**: For secure user sessions.
- **Maven**: For dependency management and project build.

### Frontend
- **React**: For building the user interface.
- **Redux Toolkit**: For state management.
- **Ant Design**: As the UI framework for building components.
- **Axios**: For making HTTP requests to the backend API.
- **ReCAPTCHA**: For preventing bot attacks during registration.

## Installation and Setup

### Prerequisites

- **Java 17**: Ensure that you have JDK 17 installed.
- **Node.js & npm**: Required for the React frontend.
- **PostgreSQL**: Ensure that PostgreSQL is installed and running.

### Backend Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/teguh-zet/teaz.git
   cd perfume-ecommerce/backend
