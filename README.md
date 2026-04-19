# 🎯 Mock Interview Practice App (Next.js + Gemini AI)

A modern web application built with **Next.js** that helps users practice mock interviews.  
Users provide a job description, and the app generates interview questions, evaluates answers, and gives a score using **Google Gemini API (2.0 Flash model)**.

---

## 🚀 Features

- 🧠 AI-generated interview questions based on job description  
- ❓ 5-question mock interview flow  
- 📝 Quiz-style questions with 4 options  
- ⏭️ Skip questions anytime  
- 🔄 Restart interview at any point  
- 📊 AI-based answer evaluation and scoring  
- 🎨 Modern and clean UI design  

---

## 🛠️ Tech Stack

- **Frontend:** Next.js (React)
- **Styling:** Tailwind CSS (or your preferred UI framework)
- **AI Integration:** Google Gemini API (2.0 Flash)
- **State Management:** React Hooks / Context API

---

## 📌 How It Works

1. User enters a **job description**
2. App sends it to **Gemini API**
3. AI generates **5 interview questions**
4. Each question:
   - Has **4 multiple-choice options**
   - User selects or skips
5. AI evaluates responses
6. Final **score is displayed**

---

## 📂 Project Structure (Example)

/app
├── /components        # Reusable UI components (buttons, cards, modals)
├── /interview         # Interview flow pages (questions, results)
├── /api               # API routes (Gemini integration)
├── /hooks             # Custom React hooks
├── /utils             # Helper functions (scoring, formatting)
├── /styles            # Global styles (Tailwind / CSS)
├── layout.js          # Root layout
└── page.js            # Home page

/public                # Static assets (images, icons)

.env                   # Environment variables (not committed)

next.config.js         # Next.js configuration
package.json           # Project dependencies

## ⚙️ Setup & Installation

### 1. Install Dependencies

```bash
npm install
```

### 2. Add Environment Variables

Create a `.env.local` file in the root directory and add:

```env
GEMINI_API_KEY=your_api_key_here
```

### 3. Run the Development Server

```bash
npm run dev
```

### 4. Open in Browser

The app will be available at:

http://localhost:3000

