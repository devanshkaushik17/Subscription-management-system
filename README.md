<<<<<<< HEAD
# SaaSify - Smart Dashboard for Subscription Management 💼🚀

![GitHub repo size](https://img.shields.io/github/repo-size/your-username/SaaSify-Dashboard-Subscription-Management?style=for-the-badge)
![GitHub stars](https://img.shields.io/github/stars/your-username/SaaSify-Dashboard-Subscription-Management?style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/your-username/SaaSify-Dashboard-Subscription-Management?style=for-the-badge)
![GitHub license](https://img.shields.io/github/license/your-username/SaaSify-Dashboard-Subscription-Management?style=for-the-badge)

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=for-the-badge&logo=framer&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

---

## 🌟 Overview
**SaaSify** is a **Full-Stack SaaS Subscription Management Dashboard** designed to help users and teams manage, analyze, and optimize their software subscriptions with smart analytics and real-time tracking.

This project demonstrates an advanced full-stack architecture using **Next.js**, **TypeScript**, **Node.js**, **Express**, and **MongoDB** — combining powerful backend logic with a sleek, interactive frontend interface.

---

## 🎯 Features

### 🔐 Authentication & Security
- **JWT Authentication** with secure cookie management
- **Password Hashing** using bcryptjs
- **CSRF Protection** for enhanced security
- **Rate Limiting** to prevent abuse
- **Helmet.js** for security headers
- **CORS Configuration** for cross-origin requests

### 👤 User Management
- **User Registration & Login** with email validation
- **Profile Management** with editable user information
- **Role-based Access Control** (Admin, Manager, User)
- **Secure Session Management**

### 💳 Subscription Management
- **Add, Edit, Delete** subscriptions with full CRUD operations
- **Category Organization** (Entertainment, Work, Tools, Other)
- **Status Tracking** (Active, Paused, Canceled)
- **Renewal Date Management** with smart notifications
- **Price Tracking** with monthly/yearly calculations

### 📊 Smart Dashboard
- **Interactive Analytics** with real-time data visualization
- **Spending Insights** and trend analysis
- **Upcoming Renewals** tracking
- **Category-wise Breakdown** of subscriptions
- **Monthly Spending Overview**

### 🎨 Modern UI/UX
- **Dark/Light Mode Toggle** with system preference detection
- **Responsive Design** for all device sizes
- **Smooth Animations** using Framer Motion
- **Modern Glass-morphism** design elements
- **Intuitive Navigation** with sidebar context

### 🔧 Technical Features
- **RESTful API** with comprehensive endpoints
- **MongoDB Atlas** database integration
- **TypeScript** for type safety
- **Modular Architecture** with clean code structure
- **Environment Configuration** management
- **Error Handling** with proper HTTP status codes

---


---

## 🛠️ Tech Stack

### 🌐 Frontend
- **React.js** (Framework: Next.js 15.5.6)
- **TypeScript** (Type Safety)
- **Tailwind CSS** (Styling)
- **Framer Motion** (Animations)
- **Lucide React** (Icons)
- **Next.js App Router** (Routing)

### 🖥️ Backend
- **Node.js** (Runtime Environment)
- **Express.js** (Web Framework)
- **TypeScript** (Type Safety)
- **MongoDB + Mongoose** (Database & ODM)
- **JWT** (Authentication)
- **bcryptjs** (Password Hashing)
- **CORS & Helmet** (Security)
- **Rate Limiting** (API Protection)

### 🗄️ Database
- **MongoDB Atlas** (Cloud Database)
- **Mongoose ODM** (Object Document Mapping)
- **Schema Validation** with TypeScript interfaces

### 🔧 Development Tools
- **ESLint** (Code Linting)
- **TypeScript Compiler** (Type Checking)
- **tsx** (TypeScript Execution)
- **Git** (Version Control)

---

## ⚙️ Installation & Setup

### 1️⃣ Prerequisites
Make sure you have the following installed on your system:
- [Node.js](https://nodejs.org/) (v18 or higher)
- [MongoDB Atlas](https://www.mongodb.com/atlas) account
- [Git](https://git-scm.com/)

### 2️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/SaaSify-Dashboard-Subscription-Management.git
cd SaaSify-Dashboard-Subscription-Management
```

### 3️⃣ Backend Setup
```bash
# Navigate to backend directory
cd backend

# Install dependencies
npm install

# Create environment file
cp .env.example .env
```

**Configure your `.env` file:**
```env
NODE_ENV=development
PORT=4000
MONGO_URL=your_mongodb_atlas_connection_string
JWT_SECRET=your_super_secret_jwt_key_here
JWT_EXPIRES_IN=7d
COOKIE_NAME=saasify_token
CORS_ORIGIN=http://localhost:3000
```

**Start the backend server:**
```bash
# Development mode
npm run dev

# Production mode
npm run build
npm start
```

### 4️⃣ Frontend Setup
```bash
# Navigate to frontend directory (in a new terminal)
cd frontend

# Install dependencies
npm install

# Start the development server
npm run dev
```

### 5️⃣ Database Setup
1. Create a MongoDB Atlas account
2. Create a new cluster
3. Get your connection string
4. Replace `your_mongodb_atlas_connection_string` in your `.env` file
5. The database will be automatically created when you first run the application

---

## 🚀 Running the Application

### Development Mode
```bash
# Terminal 1 - Backend
cd backend
npm run dev

# Terminal 2 - Frontend  
cd frontend
npm run dev
```

### Production Mode
```bash
# Build and start backend
cd backend
npm run build
npm start

# Build and start frontend
cd frontend
npm run build
npm start
```

### Access the Application
- **Frontend**: http://localhost:3000
- **Backend API**: http://localhost:4000
- **API Documentation**: http://localhost:4000/api

---

## 📁 Project Structure

```
SaaSify-Dashboard-Subscription-Management/
├── backend/
│   ├── src/
│   │   ├── config/
│   │   │   └── env.ts              # Environment configuration
│   │   ├── db/
│   │   │   └── mongoose.ts          # Database connection
│   │   ├── middleware/
│   │   │   ├── auth.ts              # JWT authentication
│   │   │   ├── csrf.ts              # CSRF protection
│   │   │   └── security.ts          # Security middleware
│   │   ├── models/
│   │   │   └── User.ts              # User model
│   │   ├── routes/
│   │   │   ├── auth.ts              # Authentication routes
│   │   │   ├── profile.ts           # User profile routes
│   │   │   ├── protected.ts         # Protected routes
│   │   │   └── csrf.ts              # CSRF routes
│   │   └── index.ts                 # Main server file
│   ├── package.json
│   └── tsconfig.json
├── frontend/
│   ├── src/
│   │   ├── app/
│   │   │   ├── auth/
│   │   │   │   ├── login/
│   │   │   │   ├── signup/
│   │   │   │   └── forgot-password/
│   │   │   ├── dashboard/
│   │   │   │   ├── analytics/
│   │   │   │   ├── billing/
│   │   │   │   ├── notifications/
│   │   │   │   ├── profile/
│   │   │   │   └── settings/
│   │   │   ├── layout.tsx
│   │   │   └── page.tsx
│   │   ├── components/
│   │   │   ├── DashboardLayout.tsx
│   │   │   ├── DashboardNavbar.tsx
│   │   │   ├── Navbar.tsx
│   │   │   └── ui/
│   │   │       └── ThemeToggle.tsx
│   │   ├── contexts/
│   │   │   ├── SidebarContext.tsx
│   │   │   └── UserContext.tsx
│   │   └── lib/
│   │       ├── api.ts
│   │       └── utils.ts
│   ├── package.json
│   └── next.config.ts
├── README.md
└── LICENSE
```

---

## 🔌 API Endpoints

### Authentication
- `POST /api/auth/register` - User registration
- `POST /api/auth/login` - User login
- `POST /api/auth/logout` - User logout
- `POST /api/auth/forgot-password` - Password reset

### User Management
- `GET /api/profile` - Get user profile
- `PUT /api/profile` - Update user profile
- `DELETE /api/profile` - Delete user account

### Protected Routes
- `GET /api/protected` - Access protected content
- `GET /api/csrf-token` - Get CSRF token

---

## 🎨 Features in Detail

### Dashboard Analytics
- **Total Subscriptions** count
- **Monthly Spending** calculation
- **Upcoming Renewals** tracking
- **Category Distribution** charts
- **Spending Trends** over time

### Subscription Management
- **Grid/List View** toggle
- **Search & Filter** functionality
- **Category Organization**
- **Status Management** (Active/Paused/Canceled)
- **Renewal Date Tracking**
- **Price Monitoring**

### User Experience
- **Responsive Design** for mobile/tablet/desktop
- **Dark/Light Theme** with system preference
- **Smooth Animations** and transitions
- **Intuitive Navigation**
- **Real-time Updates**

---

## 🔒 Security Features

- **JWT Authentication** with secure cookies
- **Password Hashing** using bcryptjs
- **CSRF Protection** for form submissions
- **Rate Limiting** to prevent abuse
- **Input Validation** with Zod schemas
- **Security Headers** with Helmet.js
- **CORS Configuration** for cross-origin requests

---

## 🚀 Deployment

### Backend Deployment (Render/Railway)
1. Connect your GitHub repository
2. Set environment variables
3. Deploy automatically on push

### Frontend Deployment (Vercel/Netlify)
1. Connect your GitHub repository
2. Configure build settings
3. Deploy automatically on push

### Environment Variables for Production
```env
NODE_ENV=production
PORT=4000
MONGO_URL=your_production_mongodb_url
JWT_SECRET=your_production_jwt_secret
JWT_EXPIRES_IN=7d
COOKIE_NAME=saasify_token
CORS_ORIGIN=https://your-frontend-domain.com
```

---

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---


## 🙏 Acknowledgments

- **Next.js** team for the amazing framework
- **Vercel** for deployment platform
- **MongoDB** for the database solution
- **Tailwind CSS** for the utility-first CSS framework
- **Framer Motion** for smooth animations
- **Lucide** for beautiful icons


---

<div align="center">


</div>
=======
# Subscription-management-system
>>>>>>> 946638bd47c6e282d034a7320864b4ae2f1edf58
