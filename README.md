# HuanPao Project

## Project Goal
HuanPao is a comprehensive health life management platform that integrates fitness check-in, points redemption, and event organization.

## Project Structure
```text
HuanPao-master/
├── client/                      # Frontend (React + Vite)  
│   ├── public/                  # Static assets (favicon, index.html)  
│   ├── src/  
│   │   ├── assets/              # Images, global styles  
│   │   ├── components/          # Reusable UI components (e.g., Navbar, Card)  
│   │   ├── pages/               # Page components (e.g., Home, Shop, Activities)  
│   │   ├── services/            # Encapsulated API calls (e.g., userService.js)  
│   │   ├── hooks/               # (Optional) Custom React hooks  
│   │   ├── App.jsx              # Main app layout and routing  
│   │   └── main.jsx             # Entry point for React app  
│   └── vite.config.js           # Vite configuration file  
│  
├── server/                      # Backend (Node.js + Express)  
│   ├── controllers/             # Business logic controllers (e.g., userController.js)  
│   ├── models/                  # MongoDB models using Mongoose  
│   ├── routes/                  # API route definitions  
│   ├── middleware/              # Middleware (auth, error handling, etc.)  
│   ├── utils/                   # Utility functions (e.g., token generation)  
│   ├── app.js                   # Main Express app entry  
│   └── .env                     # Environment variables (e.g., DB URI, JWT secret)  
│  
├── docs/                        # (Optional) Diagrams and architecture documents  
│   ├── architecture.png         # System architecture diagram  
│   └── login-flow.png           # Login and authentication flow  
│  
├── .gitignore                   # Files and folders to ignore in Git  
└── README.md                    # Project documentation  
```
## Module division

- User module: registration, login, personal information
- Check-in module: sports record upload, points record
- Mall module: redeem goods, generate orders
- Event module: create, join, view events

## How to use
