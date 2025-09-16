

# 📊 StockEase – Smart Stock Management Hub

StockEase is a **digital stock and inventory management platform** built with React + TypeScript + Firebase.
It helps businesses track stock levels, manage inventory, and monitor updates in real time with a clean, mobile-friendly UI.

---

## 🚀 Features

* **User Authentication** (Firebase Email/Password)
* **Product Management** (Add, Edit, Delete items)
* **Stock Level Tracking** (real-time Firestore updates)
* **Search & Filter** products easily
* **Low-Stock Alerts & Notifications**
* **Admin Dashboard** for stock overview
* **Responsive UI** with Tailwind CSS

---

## 🛠 Tech Stack

* **Frontend:** React + TypeScript + Vite
* **Styling:** Tailwind CSS + PostCSS
* **Backend/Database:** Firebase Firestore
* **Auth:** Firebase Authentication
* **Build Tool:** Vite
* **Linting:** ESLint
* **Package Manager:** npm / bun

---

## 📂 Project Structure

```
stockease-version-3/
│── public/             # Static assets
│── src/                # Main source code
│   ├── components/     # Reusable React components
│   └── ...             # Pages, hooks, services
│── firestore.rules     # Firestore database security rules
│── tailwind.config.ts  # Tailwind configuration
│── vite.config.ts      # Vite build configuration
│── tsconfig*.json      # TypeScript configurations
│── package.json        # Dependencies & scripts
│── postcss.config.js   # PostCSS setup
│── eslint.config.js    # ESLint setup
│── README.md           # Project documentation
```

---

## ⚙️ Installation

```bash
# Clone the repository
git clone https://github.com/Meghraj2004/StockEase-version-3.git

# Navigate to the project directory
cd StockEase-version-3

# Install dependencies (choose one)
npm install
# OR
bun install

# Start development server
npm run dev
```

---

## 🔑 Environment Variables

Create a `.env` file in the root and add your Firebase config:

```
VITE_FIREBASE_API_KEY=your_api_key
VITE_FIREBASE_AUTH_DOMAIN=your_auth_domain
VITE_FIREBASE_PROJECT_ID=your_project_id
VITE_FIREBASE_STORAGE_BUCKET=your_storage_bucket
VITE_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
VITE_FIREBASE_APP_ID=your_app_id
```

---

## 📜 Firebase Setup

1. Create a Firebase project in the [Firebase Console](https://console.firebase.google.com/).
2. Enable **Authentication** (Email/Password).
3. Set up **Firestore Database** with rules (`firestore.rules`).
4. Enable **Hosting** if deploying via Firebase.

---

## 🖥 Development

```bash
# Run development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

---

## 📌 Deployment

StockEase can be deployed on:

* **Firebase Hosting**
* **Vercel**
* **Netlify**

---

## 👨‍💻 Author

Developed by **Megharaj Dandgavhal**
GitHub: [@Meghraj2004](https://github.com/meghraj2004)
