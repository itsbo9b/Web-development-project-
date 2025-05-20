# Web-development-project-# Registration System Web Application

This is a full-stack web application that simulates a university registration system with multi-role access, authentication, and statistical data visualization. It uses modern web technologies such as **React**, **Next.js**, and **Prisma ORM**, alongside **MySQL** as the relational database.

## Project Overview

The application provides functionality for three user roles:

- **Admin**: Manages users and system data.
- **Instructor**: Manages courses and views student-related information.
- **Student**: Registers for courses and views personal academic data.

The project integrates both a modern component-based frontend and a classic static frontend:

- The **statistics page** is built using **React**, **Next.js**, **Prisma**, and **CSS**.
- The main **registration interface** is built using **pure HTML, CSS, and JavaScript**.

## Technologies Used

- HTML, CSS, JavaScript
- React & Next.js
- Prisma ORM
- MySQL
- JWT & Cookie-based Authentication
- GitHub OAuth (Third-party Authentication Provider)

## Core Features

- **Multi-role System**: Admin, Instructor, and Student dashboards with role-specific functionality.
- **Authentication**:
  - JWT tokens stored in **HTTP-only cookies** for secure session management.
  - Optional login via **GitHub OAuth** as a third-party provider.
- **Database Integration**:
  - Uses **MySQL** with **Prisma ORM** for type-safe, efficient queries.
- **Registration Interface**:
  - Built with **pure HTML, CSS, and JavaScript** to simulate basic frontend design and logic.
- **Statistics Dashboard**:
  - Developed using **React, Next.js, Prisma, and CSS**.
  - Displays dynamic aggregated data from the database, including:
    - Averages (e.g., GPA, course loads)
    - Record counts
    - Grouped metrics by role or course

## Setup Instructions

1. Install dependencies:
   ```bash
   npm install
