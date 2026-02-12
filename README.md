📖University Library Management System - "Book Wise"
Project Overview
A full-stack library management web application developed by a team of 6 developers for university-wide implementation. Built with Next.js 14, Tailwind CSS, and Firebase, this system serves as a centralized digital platform managing 50,000+ academic resources across multiple campus libraries.

Technical Architecture
Frontend: Next.js 14 (App Router) with Server-Side Rendering for optimal SEO and performance

Styling: Tailwind CSS with custom component library

Backend & Database: Firebase (Authentication, Firestore, Storage)

Deployment: Vercel with CI/CD pipeline

Version Control: Git with GitHub (feature-branch workflow)

Core Features
1. Main Page (Public Interface)
The landing page provides an intuitive gateway to the library's digital collection:

Book Discovery Section:

Dynamic book grid with infinite scroll

Real-time search with debounced input

Filter sidebar (by department, author, publication year)

Sort options (newest, most borrowed, highest rated)

Book cards displaying:

Cover image (from Firebase Storage)

Title, author, ISBN

Availability status (Available/Borrowed/Reserved)

Location code (e.g., "SCI-3rd-42B")

Quick reserve button

Featured Collections:

"New Arrivals" carousel

"Most Borrowed This Month"

"Recommended for Your Department"

"Reserved for Final Year Projects"

2. Dashboard Page (Role-Based Access)
A comprehensive analytics and management hub with three distinct views:

Student Dashboard:

Current loans with due dates

Fine summary (if applicable)

Hold requests status

Reading history

Recommended books based on borrowing pattern

Digital library card

Faculty Dashboard:

Course reserve management

Department book requests

Research material access

Inter-library loan requests

Publication alerts

Librarian Dashboard:

Real-time analytics widgets:

Total books, active loans, pending returns

Popular books chart

Peak hours heatmap

Department-wise usage statistics

Inventory alerts (low stock, damaged books)

User management interface

Fine collection tracker

Event calendar (book drives, author visits)

### Team Members (6):
-Salah Eddine Berredjem
-Ziad Abadlia
-Tesnim Lala Bouali
-Ines Goutel
-Imen Kanoua
-Mohamed Saber Tata