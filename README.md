# 💰 Personal Finance & Expense Tracker

A comprehensive MERN stack application for tracking income, expenses, and managing personal finances with beautiful analytics and reports.

## ✨ Features

- **Income & Expense Tracking** - Add, edit, delete transactions
- **Category Management** - Custom categories for better organization
- **Budget Planning** - Set monthly budgets and track spending
- **Analytics Dashboard** - Visual charts and statistics
- **Monthly Reports** - Detailed income/expense breakdowns
- **Export to CSV** - Download transaction history
- **Search & Filter** - Find transactions quickly
- **Recurring Transactions** - Auto-add monthly bills
- **Multi-currency Support** - Track in different currencies

## 🛠️ Tech Stack

**Frontend:**
- React 18
- Redux Toolkit (State Management)
- Chart.js (Analytics)
- Axios
- React Router
- Material-UI

**Backend:**
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- bcrypt

## 🚀 Installation

### Backend Setup
```bash
cd backend
npm install

# Create .env file
echo "MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PORT=5000" > .env

npm start
```

### Frontend Setup
```bash
cd frontend
npm install
npm start
```

## 📊 Features Breakdown

### Transaction Management
- Add income/expense with amount, category, date, notes
- Edit existing transactions
- Delete transactions
- Bulk delete options

### Categories
- Pre-defined categories (Food, Transport, Entertainment, etc.)
- Create custom categories
- Category-wise spending analysis
- Color-coded categories

### Budget Management
- Set monthly budget limits
- Category-wise budget allocation
- Budget vs actual spending comparison
- Alerts when approaching budget limit

### Analytics & Reports
- Monthly income/expense trends
- Category-wise pie charts
- Spending patterns
- Year-over-year comparison
- Top spending categories

### Export & Import
- Export transactions to CSV
- Import from CSV
- Backup data

## 🎨 Dashboard Features

- Total income/expense summary
- Current month statistics
- Recent transactions
- Budget progress bars
- Spending by category chart
- Monthly trend graph

## 📱 API Endpoints

### Authentication
- `POST /api/auth/register` - Register user
- `POST /api/auth/login` - Login user

### Transactions
- `GET /api/transactions` - Get all transactions
- `POST /api/transactions` - Create transaction
- `PUT /api/transactions/:id` - Update transaction
- `DELETE /api/transactions/:id` - Delete transaction
- `GET /api/transactions/stats` - Get statistics

### Categories
- `GET /api/categories` - Get all categories
- `POST /api/categories` - Create category

### Budget
- `GET /api/budget` - Get budget
- `POST /api/budget` - Set budget
- `PUT /api/budget/:id` - Update budget

## 🌐 Deployment

### Frontend (Vercel)
```bash
cd frontend
vercel --prod
```

### Backend (Railway)
```bash
cd backend
railway up
```

## 📸 Screenshots

[Add screenshots here]

## 🔮 Future Enhancements

- Mobile app (React Native)
- Bill reminders & notifications
- Investment tracking
- Savings goals
- Receipt scanning (OCR)
- Multi-user support (family accounts)
- Bank account integration

## 📄 License

MIT License

---

**Made with ❤️ by Keshav**
