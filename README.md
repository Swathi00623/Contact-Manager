# 📇 Contact Manager API

A simple **Contact Manager REST API** built using **Node.js, Express, and MongoDB**.
This project allows users to register, login, and manage their personal contacts with full CRUD operations.

---

## 🚀 Features

* User Registration
* User Login with JWT Authentication
* Create a new contact
* Get all contacts
* Search contacts
* Update contact details
* Delete contacts
* Secure API routes using authentication middleware

---

## 🛠️ Technologies Used

* Node.js
* Express.js
* MongoDB
* Mongoose
* JSON Web Token (JWT)
* bcryptjs
* dotenv
* CORS

---

## 📂 Project Structure

```
Contact-Manager
│
├── server
│   ├── controllers
│   │   ├── contactController.js
│   │   └── userController.js
│   │
│   ├── models
│   │   ├── contactModel.js
│   │   └── userModel.js
│   │
│   ├── routes
│   │   ├── contactRoutes.js
│   │   └── userRoutes.js
│   │
│   ├── middleware
│   │   ├── authMiddleware.js
│   │   └── errorHandler.js
│   │
│   ├── config
│   │   └── dbConnection.js
│   │
│   ├── server.js
│   └── package.json
```

---

## ⚙️ Installation

Clone the repository:

```
git clone https://github.com/yourusername/contact-manager.git
```

Go to the project directory:

```
cd Contact-Manager/server
```

Install dependencies:

```
npm install
```

---

## 🔑 Environment Variables

Create a `.env` file in the server folder and add:

```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

---

## ▶️ Run the Server

Start the server:

```
npm start
```

or with nodemon:

```
npm run dev
```

Server will run at:

```
http://localhost:5000
```

---

## 📡 API Endpoints

### User Authentication

**Register User**

```
POST /api/users/register
```

**Login User**

```
POST /api/users/login
```

---

### Contact Management

**Get All Contacts**

```
GET /api/contacts
```

**Create Contact**

```
POST /api/contacts
```

**Update Contact**

```
PUT /api/contacts/:id
```

**Delete Contact**

```
DELETE /api/contacts/:id
```

**Search Contact**

```
GET /api/contacts/search?name=value
```

---

## 🔒 Authentication

Most routes require a JWT token.

Add this header in requests:

```
Authorization: Bearer YOUR_TOKEN
```

---

## 🧪 Testing the API

You can test the API using:

* Postman
* Thunder Client
* cURL

---

## 📌 Future Improvements

* Add frontend using React
* Pagination for contacts
* Tag based filtering
* Contact profile pictures
* Deployment

---

## 👨‍💻 Author

Developed by **Swathi**

---

## 📜 License

This project is open source and available under the MIT License.
