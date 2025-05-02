![dashboard](https://github.com/user-attachments/assets/7a08a1d4-0162-4c4a-a5e6-47684a4f9c07)

# 💰 SpendSage: AI Finance Tracker

**SpendSage** is an AI-powered personal finance tracker that helps users manage their expenses smartly and efficiently. With intuitive visualizations, category-based tracking, and intelligent financial insights, SpendSage offers a modern alternative to traditional expense management tools.

🔗 **Live Demo**: [spendsage-ai-finance-tracking.vercel.app](https://spendsage-ai-finance-tracking.vercel.app/)

---

## 🚀 Features

- ✨ **AI-Based Financial Insights**
  - Get personalized recommendations and visual summaries powered by AI.
  
- 🧾 **Expense Tracking**
  - Add and manage expenses with ease.
  - Categorize transactions (Food, Travel, Health, etc.).
  
- 📊 **Dashboard Analytics**
  - View visual breakdowns of your spending patterns.
  - Track daily, weekly, and monthly financial trends.

- 🔐 **User Authentication**
  - Secure login system using Firebase Authentication.
  - Personalized dashboard per user.

- 💬 **Chat-Style Entry (Optional Feature)**
  - Input expenses in a natural language format (e.g., "Spent 300 on groceries").

---

## 📂 Tech Stack

| Tech           | Description                      |
|----------------|----------------------------------|
| **Next.js**    | React framework for frontend and backend |
| **Tailwind CSS** | Utility-first CSS for styling |
| **Firebase Auth** | Secure authentication for users |
| **MongoDB**    | NoSQL database for storing user expenses |
| **OpenAI API** | AI for generating financial insights (if applicable) |
| **Chart.js / Recharts** | Data visualization of expense analytics |

---

## 🏗️ Project Structure


---

## 📦 Installation

1. **Clone the repo**

```bash
git clone https://github.com/yourusername/spendsage-ai-finance-tracking.git
cd spendsage-ai-finance-tracking
MONGODB_URI=your_mongodb_connection_string
NEXT_PUBLIC_FIREBASE_API_KEY=your_firebase_key
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your_firebase_auth_domain
NEXT_PUBLIC_FIREBASE_PROJECT_ID=your_project_id
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your_storage_bucket
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
NEXT_PUBLIC_FIREBASE_APP_ID=your_app_id
OPENAI_API_KEY=your_openai_api_key (if AI features used)


npm run dev

