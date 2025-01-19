# FinanceTracker-fe
# Finance Tracker App

The Finance Tracker App is a web application designed to help users manage their finances by tracking income, expenses, and overall balance. The app provides users with the ability to log in, record financial transactions, view their current balance, and analyze spending habits through visual reports. This app is built using the MERN stack (MongoDB, Express.js, React.js, Node.js) and is deployed separately for the frontend and backend.

## Features

### User Authentication
- Users can create an account and securely log in.
- User sessions are managed to ensure data privacy.

### Income and Expense Tracking
- Users can add income and expenses with descriptions, dates, and amounts.
- Transactions are stored and categorized for easy retrieval.

### Balance Overview
- The app displays the current balance based on the logged income and expenses.
- Users can view a breakdown of their financial status at a glance.

### Financial Reports
- **Pie Charts**: Display the proportion of different categories of expenses.
- **Line Graphs**: Show income and expenses trends over time.

### Pages
- **Registration Page**: User creation interface.
- **Login Page**: User authentication interface.
- **Dashboard**: Overview of current balance and quick transaction add feature.
- **Transactions Page**: Detailed list of all transactions with options to add, edit, or delete.

## Technology Stack

### Frontend
- **React.js**
- **State Management**: Context API
- **React-Bootstrap**: For UI components
- **Charts**: Chart.js or Recharts

### Backend
- **Node.js** with Express.js
- **Database**: MongoDB (hosted on MongoDB Atlas)
- **Authentication**: JWT (JSON Web Tokens)

### Deployment
- **Frontend**: Deployed on [Netlify](https://www.netlify.com/) or [Vercel](https://vercel.com/)
- **Backend**: Deployed on [Render](https://render.com/) or [Cyclic](https://www.cyclic.sh/)

## Database Design

### Users Collection
```json
{
  "_id": ObjectId,
  "username": String,
  "email": String (unique),
  "password": String (hashed),
  "createdAt": Date
}
