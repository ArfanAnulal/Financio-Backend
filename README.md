# Financio Backend

This is the backend server for **Financio**, a modern personal finance management application built using the **MERN** stack. It provides a RESTful API to manage user authentication, transactions, and account data.

The frontend of this project is available at [Frontend Repo](https://github.com/ArfanAnulal/Financio-Frontend).

## 📚 Table of Contents

- [🚀 Features](#-features)
- [📦 Tech Stack](#-tech-stack)
- [🔧 Setup & Development](#-setup--development)
  - [1. Clone the repository](#1-clone-the-repository)
  - [2. Install dependencies](#2-install-dependencies)
  - [3. Configure environment variables](#3-configure-environment-variables)
  - [4. Run the server](#4-run-the-server)
  - [5. Deployment](#5-deployment)
- [📄 License](#license)

## 🚀 Features

- RESTful API for users, accounts, and transactions
- Implemented CRUD operations
- MongoDB database integration
- Environment-based configuration

## 📦 Tech Stack

- **Node.js** with **Express.js**
- **MongoDB** with **Mongoose**
- **dotenv** for environment management
- **CORS** for security

## 🔧 Setup & Development

### 1. Clone the repository

```bash
git clone https://github.com/your-username/financio-backend.git
cd financio-backend
```

### 2. Install dependencies
```bash
npm install
```

### 3. Configure environment variables
Create a `.env` file 
in the root of the project and add:
```bash
MONGO_URI=your-mongodb-connection-string
```

- You can get a connection string from MongoDB Atlas or use a local MongoDB instance.

### 4. Run the development server
```bash
node index.js
```

### 5. Deployment
You can deploy this backend to any Node.js-compatible hosting service such as:

- Render
- Railway
- Heroku
- VPS/Cloud (e.g., DigitalOcean, AWS EC2)

Make sure to set the `MONGO_URI` and any other environment variables in your deployment environment.

## License
This project is open-source and available under the MIT License.
