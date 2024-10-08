﻿# JobBee-Website
JobBee is a full-stack web application designed to help job seekers find job listings and manage their applications. Built using the MERN stack (MongoDB, Express, React, Node.js), JobBee provides a seamless user experience for both job seekers and Employers.

## Features
- **User authentication and authorization**
- **Job listing and searching**
- **Application tracking**
- **User profiles**
- **Admin panel for managing jobs and users**

## Tech Stack
- **Frontend:** React, Redux, Bootstrap
- **Backend:** Node.js, Express
- **Database:** MongoDB
- **Authentication:** JWT (JSON Web Tokens)

## Installation
### Prerequisites
Make sure you have the following installed:
- Node.js
- MongoDB
- Git

### Steps
1. Clone the repository:
   ```sh
   git clone https://github.com/Aditya-Jani/jobBee-Website.git
   cd jobBee-Website

## Make sure to crate a config.env file inside backend/config
PORT = 4000 
CLOUDINARY_CLIENT_NAME=XXXXXXXX

CLOUDINARY_CLIENT_API= XXXXXXXXX

CLOUDINARY_CLIENT_SECRET=XXXXXXXXXX

FRONTEND_URL = http://localhost:5173

MONGO_URI = mongodb://127.0.0.1:27017

JWT_SECRET_KEY = XXXXXXXX

JWT_EXPIRE = 10d

COOKIE_EXPIRE = 5

## Run Application

Terminal 1

- cd .\backend\
- npm run dev
  
Terminal 2

- cd .\frontend\
- npm run dev
