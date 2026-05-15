# L-F-system
A small system for lost and found to keep everything in a simple and organized website. 
# Lost & Found Web Application

## Project Description
Lost & Found is a full-stack web application that allows users to report, view, and claim lost or found items. Users can upload items with images, search through listings, and mark items as claimed.

The application uses a frontend built with HTML, CSS, and JavaScript, and a backend powered by Firebase Firestore for real-time data storage.

---

## Problem Being Solved
Many schools and communities struggle to efficiently track lost and found items. Items are often misplaced without a proper system for reporting or retrieving them.

This project solves that problem by providing a centralized digital platform where users can:
- Report lost items
- Post found items
- Search listings easily
- Claim items when recovered

---

## Features
- Add lost and found items
- Upload item images
- Search and filter items
- Claim lost items
- Real-time database updates (Firebase)
- Responsive user interface
- Dynamic item rendering

---

## Frontend Technologies Used
- HTML
- CSS
- JavaScript

### Frontend Responsibilities:
- User interface design
- Displaying items in a grid layout
- Handling user interactions
- Searching and filtering items
- Opening item details in a modal

---

## Backend Technologies Used
- Firebase Firestore

### Backend Responsibilities:
- Storing item data in the cloud
- Handling create, read, and update operations
- Updating item status when claimed
- Providing real-time data syncing between users

---

## Data Storage Explanation
This project uses **Firebase Firestore** as its primary database.

The storage system is used for:
- Saving item details (name, description, type, image)
- Updating item status (lost → found when claimed)
- Persisting data across all users and sessions
- Enabling real-time updates

Images are currently stored as base64 strings inside the database (can be upgraded to Firebase Storage in the future).

---

## Tech Stack Overview

### Frontend
- HTML
- CSS
- JavaScript

### Backend
- Firebase Firestore (No custom server required)

### Data Storage
- Cloud-based NoSQL database (Firestore)

---

## Development Tools
- Visual Studio Code
- Firebase Console
- GitHub
- Google Chrome Developer Tools

---

## Language & Framework Justification
JavaScript was chosen for frontend logic because it allows dynamic updates, event handling, and real-time UI interaction.

Firebase Firestore was chosen as the backend because it:
- Requires no server setup
- Provides real-time database updates
- Is easy to integrate with JavaScript
- Supports scalable cloud storage

---

## Installation Instructions

### Required Software
Before running the project, install:
- Visual Studio Code
- Google Chrome (or any browser)

---

## Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/lost-found-app.git
