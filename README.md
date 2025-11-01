# <div align="center">💰 MERN Fullstack Expense Tracker</div>

<div align="center">

A comprehensive, full-stack personal finance management application built with the MERN stack (MongoDB, Express.js, React, Node.js). This application provides users with powerful tools to track expenses, manage income, visualize financial data, and gain insights into their spending habits through beautiful charts and analytics.

![License](https://img.shields.io/badge/license-MIT-blue.svg) ![MongoDB](https://img.shields.io/badge/MongoDB-Latest-green.svg) ![Express](https://img.shields.io/badge/Express-5.1.0-yellow.svg) ![React](https://img.shields.io/badge/React-19.1.0-blue.svg) ![Node.js](https://img.shields.io/badge/Node.js-v18+-green.svg)

</div>

<div align="justify">

## 🌟 Overview

The MERN Fullstack Expense Tracker is designed to help individuals take control of their personal finances through:

- **Comprehensive Expense Tracking**: Categorize and monitor all your expenses with detailed analytics
- **Income Management**: Track multiple income sources and analyze earning patterns
- **Visual Analytics**: Beautiful charts and graphs powered by Recharts for data visualization
- **Secure Authentication**: JWT-based authentication system with profile management
- **Real-time Updates**: Live data synchronization across all devices
- **Export Capabilities**: Download financial data as Excel files for external analysis
- **Responsive Design**: Works seamlessly across desktop, tablet, and mobile devices

## 🚀 Live Demo

🔗 **[View Live Application](https://expense-app-gbzc-git-main-shindesahil321s-projects.vercel.app/login)** 

## 📸 Screenshots

### Dashboard Overview

![Dashboard](./screenshots/dashboard.png)

### Expense Analytics

![Analytics](./screenshots/analytics.png)

### Mobile View

![Mobile](./screenshots/mobile.png)

## ✨ Key Features

### 🔐 **Authentication & Security**

- Secure user registration and login system
- JWT-based authentication with token refresh
- Password encryption using bcrypt
- Protected routes and middleware
- User profile management with image upload
- Account deletion with data cleanup

### 💸 **Expense Management**

- Add, edit, and delete expense entries
- Categorize expenses with custom categories
- Emoji-based category icons for visual appeal
- Date-based expense filtering and sorting
- Bulk operations for managing multiple expenses
- Excel export functionality for expense data

### 💰 **Income Tracking**

- Multiple income source tracking
- Income categorization and organization
- Monthly and yearly income analysis
- Visual income distribution charts
- Income vs expense comparison tools
- Comprehensive income reporting

### 📊 **Analytics & Visualization**

- Interactive pie charts for expense distribution
- Bar charts for monthly/yearly trends
- Line charts for spending patterns over time
- Financial overview with balance calculations
- Recent transactions display
- Custom date range analytics

### 🎨 **User Experience**

- Modern, clean interface design
- Responsive mobile-first design
- Real-time toast notifications
- Smooth animations and transitions
- Intuitive navigation and user flow
- Dark/light theme support (planned)

### 📁 **Data Management**

- Secure cloud data storage
- Real-time data synchronization
- Data export capabilities
- Backup and restore functionality
- Data visualization export

## 🛠️ Technology Stack

### **Backend Technologies**

- **Node.js** - JavaScript runtime environment
- **Express.js 5.1.0** - Web application framework
- **MongoDB** - NoSQL database for data storage
- **Mongoose 8.17.0** - MongoDB object modeling
- **JWT** - JSON Web Tokens for authentication
- **bcryptjs** - Password hashing and security
- **Multer** - File upload handling
- **CORS** - Cross-origin resource sharing
- **dotenv** - Environment variable management

### **Frontend Technologies**

- **React 19.1.0** - User interface library
- **Vite 7.0.4** - Build tool and development server
- **React Router DOM 7.7.1** - Client-side routing
- **Tailwind CSS 4.1.11** - Utility-first CSS framework
- **Axios 1.11.0** - HTTP client for API requests
- **Recharts 3.1.0** - Data visualization library
- **React Hot Toast** - Toast notifications
- **Emoji Picker React** - Emoji selection component
- **Moment.js** - Date manipulation and formatting

### **Development Tools**

- **ESLint** - Code linting and quality assurance
- **Prettier** - Code formatting
- **Nodemon** - Development server auto-restart
- **Concurrently** - Run multiple scripts simultaneously

## 📁 Project Structure

```
Fullstack-MERN-Expense-Tracker/
├── BackEnd/                          # Backend API Server
│   ├── config/
│   │   └── db.js                     # MongoDB connection
│   ├── controllers/
│   │   ├── authController.js         # Authentication logic
│   │   ├── dashboardController.js    # Dashboard data
│   │   ├── expenseController.js      # Expense operations
│   │   └── incomeController.js       # Income operations
│   ├── middleware/
│   │   ├── authMiddleware.js         # JWT verification
│   │   └── uploadMiddleware.js       # File upload handling
│   ├── models/
│   │   ├── User.js                   # User data model
│   │   ├── Expense.js                # Expense data model
│   │   └── Income.js                 # Income data model
│   ├── routes/
│   │   ├── authRoutes.js             # Authentication endpoints
│   │   ├── dashboardRoutes.js        # Dashboard endpoints
│   │   ├── expenseRoutes.js          # Expense endpoints
│   │   └── incomeRoutes.js           # Income endpoints
│   ├── uploads/                      # User uploaded files
│   ├── server.js                     # Main server file
│   ├── package.json                  # Backend dependencies
│   └── README.md                     # Backend documentation
├── FrontEnd/                         # React Frontend Application
│   ├── public/
│   │   └── vite.svg                  # App favicon
│   ├── src/
│   │   ├── assets/                   # Static assets
│   │   ├── components/               # React components
│   │   │   ├── Cards/                # Card components
│   │   │   ├── Charts/               # Chart components
│   │   │   ├── Dashboard/            # Dashboard components
│   │   │   ├── Expense/              # Expense components
│   │   │   ├── Income/               # Income components
│   │   │   ├── Inputs/               # Form input components
│   │   │   ├── layouts/              # Layout components
│   │   │   └── Profile/              # Profile components
│   │   ├── context/                  # React Context providers
│   │   ├── hooks/                    # Custom React hooks
│   │   ├── pages/                    # Page components
│   │   │   ├── Auth/                 # Authentication pages
│   │   │   └── Dashboard/            # Dashboard pages
│   │   ├── utils/                    # Utility functions
│   │   ├── App.jsx                   # Main App component
│   │   ├── main.jsx                  # App entry point
│   │   └── index.css                 # Global styles
│   ├── package.json                  # Frontend dependencies
│   ├── vite.config.js                # Vite configuration
│   └── README.md                     # Frontend documentation
├── screenshots/                      # Application screenshots
├── LICENSE                           # MIT License
└── README.md                         # This file
```

## 🚀 Quick Start Guide

### Prerequisites

Before you begin, ensure you have the following installed:

- **Node.js** (v18 or higher) - [Download here](https://nodejs.org/)
- **MongoDB** (local installation or MongoDB Atlas account) - [Setup guide](https://www.mongodb.com/docs/manual/installation/)
- **Git** - [Download here](https://git-scm.com/)
- **npm** or **yarn** package manager

### Installation Steps

#### 1. Clone the Repository

```bash
git clone <your-repository-url>
cd MERN-Fullstack-Expense-Tracker
```

#### 2. Backend Setup

```bash
# Navigate to backend directory
cd BackEnd

# Install backend dependencies
npm install

# Create environment file
cp .env.example .env

# Configure your environment variables in .env file
# MONGO_URI=mongodb://localhost:27017/expense-tracker
# JWT_SECRET=your-super-secret-jwt-key
# PORT=5000
# CLIENT_URL=http://localhost:5173

# Start the backend server
npm run dev
```

#### 3. Frontend Setup

```bash
# Open a new terminal and navigate to frontend directory
cd FrontEnd

# Install frontend dependencies
npm install

# Update API base URL in src/utils/apiPaths.js if needed
# export const BASE_URL = "http://localhost:5000";

# Start the frontend development server
npm run dev
```

#### 4. Access the Application

- **Frontend**: Open [http://localhost:5173](http://localhost:5173) in your browser
- **Backend API**: Backend server runs on [http://localhost:5000](http://localhost:5000)

### 🗄️ Database Setup

#### Option 1: Local MongoDB

```bash
# Install MongoDB Community Edition
# Start MongoDB service
mongod

# The application will connect to mongodb://localhost:27017/expense-tracker
```

#### Option 2: MongoDB Atlas (Cloud)

1. Create a free MongoDB Atlas account
2. Create a new cluster
3. Get your connection string
4. Update `MONGO_URI` in your `.env` file

### 🔧 Environment Configuration

#### Backend Environment Variables (`.env`)

```env
# Database Configuration
MONGO_URI=mongodb://localhost:27017/expense-tracker
# or for MongoDB Atlas:
# MONGO_URI=mongodb+srv://username:password@cluster.mongodb.net/expense-tracker

# JWT Configuration
JWT_SECRET=your-super-secret-jwt-key-minimum-32-characters-long

# Server Configuration
PORT=5000
NODE_ENV=development

# Client Configuration (CORS)
CLIENT_URL=http://localhost:5173
```

#### Frontend Configuration

Update API endpoints in `FrontEnd/src/utils/apiPaths.js`:

```javascript
export const BASE_URL =
  process.env.NODE_ENV === "production"
    ? "https://your-production-api.com"
    : "http://localhost:5000";
```

## 📚 Detailed Documentation

### 🔗 Component Documentation

For detailed information about each part of the application, please refer to the respective README files:

#### 📖 [Backend Documentation](./BackEnd/README.md)

Comprehensive guide covering:

- API endpoints and authentication
- Database models and relationships
- Server configuration and middleware
- Security implementation
- Deployment instructions
- Testing and development workflow

#### 📖 [Frontend Documentation](./FrontEnd/README.md)

Detailed documentation including:

- Component architecture and design system
- State management and routing
- UI/UX implementation details
- Responsive design approach
- Performance optimization
- Build and deployment process

## 🔌 API Endpoints Overview

### Authentication Endpoints

```http
POST /api/v1/auth/register     # User registration
POST /api/v1/auth/login        # User login
GET  /api/v1/auth/getUser      # Get user profile
POST /api/v1/auth/upload-image # Profile image upload
DELETE /api/v1/auth/deleteAccount # Delete user account
```

### Expense Management

```http
GET    /api/v1/expense/get     # Get all expenses
POST   /api/v1/expense/add     # Create new expense
PUT    /api/v1/expense/:id     # Update expense
DELETE /api/v1/expense/:id     # Delete expense
GET    /api/v1/expense/downloadexcel # Export expenses
```

### Income Management

```http
GET    /api/v1/income/get      # Get all income
POST   /api/v1/income/add      # Create new income
PUT    /api/v1/income/:id      # Update income
DELETE /api/v1/income/:id      # Delete income
GET    /api/v1/income/downloadexcel # Export income
```

### Dashboard & Analytics

```http
GET /api/v1/dashboard          # Get dashboard data
GET /api/v1/dashboard/overview # Financial overview
GET /api/v1/dashboard/analytics # Advanced analytics
```

## 🎨 UI/UX Features

### Design Principles

- **Minimalist Design**: Clean, uncluttered interface focused on usability
- **Consistent Typography**: Poppins font family for modern, readable text
- **Color Psychology**: Purple primary color for trust, green for income, red for expenses
- **Responsive Layout**: Mobile-first approach with Tailwind CSS utilities

### Interactive Elements

- **Hover Effects**: Subtle animations on buttons and cards
- **Loading States**: Skeleton screens and loading indicators
- **Toast Notifications**: Real-time feedback for user actions
- **Modal Dialogs**: Confirmation dialogs for destructive actions
- **Form Validation**: Real-time input validation with error messages

### Accessibility Features

- **Keyboard Navigation**: Full keyboard accessibility support
- **Screen Reader Support**: Proper ARIA labels and semantic HTML
- **Color Contrast**: WCAG-compliant color contrast ratios
- **Focus Indicators**: Clear focus states for interactive elements

## 🔒 Security Features

### Backend Security

- **Password Hashing**: bcrypt with salt rounds for secure password storage
- **JWT Authentication**: Secure token-based authentication system
- **Input Validation**: Server-side validation for all API endpoints
- **CORS Protection**: Configured CORS policy for frontend integration
- **Rate Limiting**: Protection against brute force attacks (planned)
- **Data Sanitization**: Protection against injection attacks

### Frontend Security

- **Token Management**: Secure JWT token storage and automatic renewal
- **Input Sanitization**: Client-side input validation and sanitization
- **HTTPS Enforcement**: Secure communication in production
- **Environment Variables**: Sensitive data stored in environment variables
- **Content Security Policy**: CSP headers for XSS protection (planned)

## 📊 Performance Optimizations

### Backend Performance

- **Database Indexing**: Optimized MongoDB indexes for fast queries
- **Connection Pooling**: Efficient database connection management
- **Middleware Optimization**: Lightweight middleware for request processing
- **Caching Strategy**: Planned Redis integration for session caching
- **API Rate Limiting**: Planned rate limiting for API protection

### Frontend Performance

- **Code Splitting**: Automatic route-based code splitting with Vite
- **Tree Shaking**: Elimination of unused code in production builds
- **Asset Optimization**: Optimized images and static assets
- **Lazy Loading**: Component lazy loading for improved load times
- **Bundle Analysis**: Regular bundle size monitoring and optimization



### Code Style

- **Backend**: Follow Node.js best practices and Express.js conventions
- **Frontend**: Use React best practices with functional components and hooks
- **CSS**: Utilize Tailwind CSS utility classes consistently
- **JavaScript**: Use ES6+ features and async/await for promises


- [ ] **Team Accounts**: Business expense tracking for teams
- [ ] **Advanced Reporting**: Custom reports and analytics
- [ ] **API Access**: Public API for third-party integrations
- [ ] **White-label Solution**: Customizable branding for businesses
- [ ] **Advanced Security**: Two-factor authentication, audit logs

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### License Summary

- ✅ **Commercial Use**: Use for commercial projects
- ✅ **Modification**: Modify the source code
- ✅ **Distribution**: Distribute the software
- ✅ **Private Use**: Use for private projects
- ❗ **Liability**: Software provided "as is"
- ❗ **Warranty**: No warranty provided

## 👨‍💻 Author & Maintainer

**Sahil Shinde**

- 🐙 **GitHub**: [@sahilshinde-dev]
- 💼 **LinkedIn**: [Your LinkedIn Profile]
- 🌐 **Portfolio**: [Your Portfolio Website]
- 📧 **Email**: [your.email@example.com]

