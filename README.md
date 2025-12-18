# PDF Hunt – Engineering ’25 Resources

A modern, responsive web application for organizing and sharing educational resources (PDFs, Drive links, and more). Built with **React**, **Vite**, **Tailwind CSS**, and **Firebase**.

---

## 🚀 Features

- **Resource Organization**: Browse materials by categories (Udvash, ACS, Others) with nested folders.
- **PDF Preview**: Read documents directly in the app using an integrated PDF viewer.
- **Admin Panel**: Secure UI to add, edit, move, and delete files/folders—no coding required.
- **Settings Editor**: Customize app name, tab names, and color themes from the interface.
- **Dark Mode**: Fully supported light/dark theme toggle.
- **PWA Support**: Installable on mobile and desktop for offline-like access.
- **Search**: Instant search across all folders and resources.

---

## 🛠️ Tech Stack

- **Frontend**: React (Vite)
- **Styling**: Tailwind CSS + Lucide Icons
- **Backend**: Firebase Firestore 
- **Authentication**: Firebase Authentication (Anonymous + Custom)
- **Hosting**: Firebase Hosting

---

## 💻 Getting Started (Local Setup)

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/marjuk06/acs-engineering-25.git
cd acs-engineering-25
```

### 2️⃣ Install Dependencies

```bash
npm install
```

### 3️⃣ Configure Firebase

- Create a Firebase project.
- Enable **Authentication (Anonymous)** and **Firestore**.
- Add your Firebase credentials in `firebaseConfig.js` or update them in `src/App.jsx`.

### 4️⃣ Run the Development Server

```bash
npm run dev
```

---

## 🔐 Admin Access

1. Click the **Profile** icon in the bottom navigation.
2. Select **“Login to Admin Console”**.
3. Enter the secure PIN.

> **Default PIN:** `140075` (Change this before production use.)

---

## 📦 Deployment (Firebase Hosting)

### Build the Project

```bash
npm run build
```

### Deploy

```bash
firebase deploy
```

---

## 📱 Mobile Development Preview

To test on your phone during local development:

```bash
npx vite --host
```

Open the **Network URL** shown in the terminal on your mobile browser.

---

## 📁 Project Structure (Simplified)

```
acs-engineering-25/
├─ src/
│  ├─ components/
│  ├─ pages/
│  ├─ services/
│  ├─ styles/
│  └─ App.jsx
├─ public/
├─ firebase.json
└─ vite.config.js
```

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 🙌 Acknowledgements

Built to simplify access to Engineering ’25 study resources with a fast, scalable, and user-friendly interface.
