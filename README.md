# Wanderlust

A simple Airbnb-style full-stack web app where users can **add listings**, **delete listings**, **book stays**, and **give reviews/feedback**.

## Features

* User Login/Signup (JWT Auth)
* Add / Edit / Delete Listings (Hosts)
* Browse & Search Properties (Users)
* Booking System with Date Selection
* Reviews & Ratings Section
* Image Upload (Cloudinary / Local)

## Tech Stack

* **Frontend:** React + Tailwind / CSS
* **Backend:** Node.js + Express
* **Database:** MongoDB + Mongoose
* **Auth:** JWT + bcrypt
* **Storage:** Cloudinary (optional)

## Folder Structure

```
/client
  /src (UI, pages, components, API calls)
/server
  /models
  /routes
  /controllers
  server.js
```

## Setup

```
git clone <repo-url>
cd wanderlust
cd server && npm install
cd ../client && npm install
```

### Run

```
# Backend
cd server
npm run dev

# Frontend
cd client
npm start
```

## API Overview

* POST /auth/register
* POST /auth/login
* GET /listings
* POST /listings (host)
* DELETE /listings/:id
* POST /bookings
* POST /reviews

## Environment Variables (`server/.env`)

```
MONGO_URI=...
JWT_SECRET=...
CLOUD_NAME=...
CLOUD_KEY=...
CLOUD_SECRET=...
```

## Deployment

* Frontend: Vercel / Netlify
* Backend: Render / Railway
* Database: MongoDB Atlas





