QuickAI SaaS Platform

A full-stack AI-powered SaaS application that enables users to generate articles, create AI images, remove image backgrounds, review resumes, and access premium features through a subscription-based model.

Overview

QuickAI is a modern SaaS platform built using React, Node.js, PostgreSQL, and AI APIs. The application provides multiple AI-powered tools through a secure and scalable architecture.

Features

- AI Article Generation
- AI Image Generation
- Background Removal
- Object Removal
- Resume Review
- Blog Title Generator
- User Authentication
- Free and Premium Subscription Plans
- Cloud Image Storage

Tech Stack

Frontend

- React.js
- Vite
- JavaScript
- CSS

Backend

- Node.js
- Express.js

Database

- PostgreSQL
- Neon Database

Authentication

- Clerk Authentication

AI Integrations

- Google Gemini API
- Clipdrop API

Cloud Storage

- Cloudinary

Deployment

- Vercel

Project Structure

QuickAI-SaaS
│
├── client
│   ├── src
│   ├── public
│   ├── assets
│   └── package.json
│
├── server
│   ├── controllers
│   ├── routes
│   ├── middlewares
│   ├── configs
│   ├── server.js
│   └── package.json
│
└── README.md

Installation

Clone Repository

git clone https://github.com/Chintu819/QuickAI-SaaS.git

Install Frontend Dependencies

cd client
npm install

Install Backend Dependencies

cd ../server
npm install

Environment Variables

Create a ".env" file inside the server folder and add:

DATABASE_URL=

CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

GEMINI_API_KEY=
CLIPDROP_API_KEY=

CLOUDINARY_CLOUD_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=

Running the Project

Start Backend Server

cd server
npm run server

Backend URL:

http://localhost:3000

Start Frontend

cd client
npm run dev

Frontend URL:

http://localhost:5173

Key Learning Outcomes

- Full Stack Web Development
- REST API Development
- Authentication and Authorization
- PostgreSQL Database Management
- AI API Integration
- SaaS Application Development
- Cloud Storage Integration
- Production Deployment

Author

Chintu Kumar

Software Engineering Student
Full Stack Developer
AI Enthusiast

GitHub:
https://github.com/Chintu819

License

This project is licensed under the MIT License.
