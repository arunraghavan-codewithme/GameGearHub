# 🎮 GameGearHub

![React](https://img.shields.io/badge/React-18-61DAFB?logo=react&logoColor=black)
![Redux Toolkit](https://img.shields.io/badge/Redux_Toolkit-764ABC?logo=redux&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?logo=tailwindcss&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-18-339933?logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?logo=socketdotio&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?logo=stripe&logoColor=white)
![Cloudinary](https://img.shields.io/badge/Cloudinary-3448C5?logo=cloudinary&logoColor=white)

## 📖 Introduction

**GameGearHub** is a campus-exclusive marketplace for the Universiti Sains Malaysia (USM) community. Students and staff can buy, sell, and exchange gaming gear, electronics, study materials, and other campus essentials in a trusted, campus-only environment. It encourages reuse and a circular economy inside the university.

It is a full-stack MERN-style web app (MongoDB, Express, React, Node.js) with real-time chat, and was built as a team project for **CAT201 – Integrated Software Development Workshop** at USM.

## 🛠️ Technologies Used

**Frontend**
- React 18 (Create React App) and React Router
- Redux Toolkit for state management
- Tailwind CSS and Material UI for styling
- Axios for API calls
- Stripe and PayPal React libraries for payments
- React Toastify, React Icons, Lottie animations
- React Testing Library and Jest

**Backend**
- Node.js 18 and Express
- MongoDB with Mongoose
- JWT authentication with cookies, bcrypt password hashing
- Nodemailer for email (verification)
- Cloudinary for image uploads
- Stripe for payments
- Vercel deployment config

**Real-time server**
- Socket.IO with Express (separate `socket` service)

**Design**
- Figma wireframes and user flows

## ✨ Features

- Secure registration and login with email verification
- Separate buyer and seller accounts, with a "Become a Seller" flow
- Product browsing across 10 categories (Computers and Laptops, Mobile and Tablets, Music and Gaming, Study Materials, Sports and Fitness, Clothes, Accessories, Cosmetics and Body Care, Desa Essentials, Others)
- Search and product filtering
- Best Selling page and Events page
- Wishlist and shopping cart
- Online payments (Stripe)
- Image uploads for profiles and products (Cloudinary)
- Real-time messaging (Socket.IO)
- FAQ and support section
- Responsive design for desktop and mobile

## 🙋 What Users Can Do

- **Buyers:** create an account, verify their email, search and filter products, save items to a wishlist, add items to a cart, and pay online.
- **Sellers:** register a shop, upload products with images, and manage their listings.
- **Everyone:** chat in real time, check events, and read the FAQ.

<!-- TODO: Keyboard shortcuts section is left out because the app has none that I know of. Add one here if you built any. -->

## 🧱 How I Built It

1. **Planned the project** with my team: split the work into frontend, backend, and content, and agreed on the structure (`frontend`, `backend`, `socket`).
2. **Set up the project environment**, including the React app and the Node.js/Express server.
3. **Built authentication**: registration, login, email verification, and secure password handling.
4. **Connected the pieces**: frontend to API, API to MongoDB, plus the real-time socket server.
5. **Reviewed and debugged** teammates' code, and checked security and data validation.
6. **Deployed** the app using the Vercel configuration in the backend.

<!-- TODO: Edit this list so it matches what you actually did, in your own words. -->

## 📚 What I Learned

- Building a full-stack app with separate frontend, backend, and real-time services
- Implementing secure authentication with JWT, cookies, and password hashing
- Managing global state with Redux Toolkit
- Working as a team on Git and GitHub, including code review
- Keeping secrets such as API keys out of a public repository

<!-- TODO: Replace with your real lessons. Recruiters like specific stories (a bug you fixed, a decision you made). -->

## 🔮 How It Could Be Improved

- Add automated tests for the backend and key frontend components
- Add ratings and reviews for sellers
- Improve search with better filtering and sorting
- Add an admin dashboard for moderation
- Add order tracking and notifications

## 🚀 How to Run the Project

### Prerequisites
- [Node.js 18](https://nodejs.org/) and npm
- A [MongoDB](https://www.mongodb.com/) database (local or Atlas)
- Accounts for Cloudinary and Stripe (for images and payments)

### 1. Clone the repo
```bash
git clone https://github.com/arunraghavan-codewithme/GameGearHub.git
cd GameGearHub
```

### 2. Backend
```bash
cd backend
npm install
npm run dev
```

### 3. Socket server (new terminal)
```bash
cd socket
npm install
npm start
```

### 4. Frontend (new terminal)
```bash
cd frontend
npm install
npm start
```

The app opens at `http://localhost:3000`.

### Environment variables

Create a `.env` file in `backend` (and `socket` if needed). **Never commit real secrets.**

```env
# Example names only - replace with your own values
PORT=
DB_URL=
JWT_SECRET_KEY=
CLOUDINARY_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=
STRIPE_SECRET_KEY=
SMTP_HOST=
SMTP_MAIL=
SMTP_PASSWORD=
```

<!-- TODO: Replace these with the real variable names from your backend code. -->

## 🎥 Demo Video

<!-- Drag your short video (under a minute) into the GitHub editor and paste the link it generates here. -->

*Demo video coming soon.*

## 👥 Team

| Member | Role |
|---|---|
| **Arunpillai A/L Raghavan** ([@arunraghavan-codewithme](https://github.com/arunraghavan-codewithme)) | Project Lead and Full-Stack Developer: project structure, authentication, environment setup, deployment, code review |
| **Heriss Raj A/L Ravi** | UI/UX Designer and Frontend Developer: Figma designs, React components, styling, branding |
| **Sharvvesh A/L Sukumaran** ([@SharrSuku](https://github.com/SharrSuku)) | Backend Developer and Content Manager: data structure, product filtering, wishlist, FAQ content |

Original repository: [SharrSuku/GameGearHub](https://github.com/SharrSuku/GameGearHub)

## 📄 License

Created for academic purposes at Universiti Sains Malaysia.
