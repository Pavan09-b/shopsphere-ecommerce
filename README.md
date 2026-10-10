# ShopSphere 🛒

ShopSphere is a full-stack e-commerce web application that provides a smooth online shopping experience with product browsing, cart management, secure authentication, and online payments.

## Features

- User registration and login with JWT authentication
- Product browsing, categories, and brands
- Shopping cart and order management
- Address management during checkout
- Product image uploads using Cloudinary
- Online payments using Razorpay
- Email functionality
- Admin dashboard for managing products, users, and orders

## Tech Stack

- **Frontend:** React.js, Vite, Redux
- **Backend:** Node.js, Express.js
- **Database:** MongoDB, Mongoose
- **Authentication:** JWT, bcrypt
- **Integrations:** Cloudinary, Razorpay, Nodemailer

## Project Structure

```text
ShopSphere/
├── backend/
├── frontend/
└── README.md
```

## Getting Started

### Prerequisites

- Node.js and npm
- MongoDB database

### Backend Setup

```bash
cd backend
npm install
```

Create a `backend/.env` file using `backend/sample.env` as a template and provide your own required credentials.

Start the backend using the appropriate script defined in `backend/package.json`.

### Frontend Setup

Open a separate terminal:

```bash
cd frontend
npm install
```

Configure the required frontend environment variables, if applicable, and start the app using the script defined in `frontend/package.json`.

## Security

Never commit `.env` files, database credentials, JWT secrets, or private API keys.

## Author

**Pavan**

GitHub: [Pavan09-b](https://github.com/Pavan09-b)

---

Built as a full-stack e-commerce project.