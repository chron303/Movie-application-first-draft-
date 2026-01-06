# 🎬 Movie Mobile App (Expo + Appwrite)

A movie discovery mobile application built with **Expo**, **Expo Router**, and **Appwrite**.  
This repository contains the **first draft** of the project, focusing on navigation, UI structure, and backend integration.

---

## 🚀 Tech Stack

- **Expo (React Native)**
- **Expo Router** – file-based routing
- **Appwrite** – backend (database & analytics)
- **TMDB API** – movie data
- **NativeWind / Tailwind CSS** – styling

---

## 📱 Features (Current Draft)

- Movie listing UI
- Dynamic movie detail pages
- Tab-based navigation
- Search tracking stored in Appwrite
- Trending movies based on search frequency
- Custom icons, images, and fonts
- File-based routing with Expo Router

> ⚠️ This is an early draft. Structure and features will evolve.

---

## 📁 Project Structure



---

## 🔧 Environment Variables

Create a `.env` file in the project root (this file is **ignored by Git**):

EXPO_PUBLIC_MOVIE_API_KEY=your_tmdb_api_key
EXPO_PUBLIC_APPWRITE_PROJECT_ID=your_appwrite_project_id
EXPO_PUBLIC_APPWRITE_DATABASE_ID=your_database_id
EXPO_PUBLIC_APPWRITE_COLLECTION_ID=metrics


---

## ▶️ Getting Started

### 1️⃣ Install dependencies

npm install


### 2️⃣ Start the development server

npx expo start


You can run the app using:
- Expo Go (Android)
- Android Emulator
- USB debugging (ADB reverse) for restricted networks

---

## 🧠 Important Notes

- This project uses **Expo Router**, so there is **no `App.tsx`**
- Entry point is handled via:

import 'expo-router/entry';

- Appwrite uses **region-specific endpoints**
- `.env` must never be committed

---

## 🛠️ Planned Improvements

- Authentication
- Watchlist / saved movies
- Skeleton loaders
- Better error handling
- Performance optimizations
- UI/UX improvements
- Production builds

---

## 📌 Project Status

🟡 **Active Development — First Draft**

This repository represents a checkpoint before major refactors and feature additions.

---

## 📄 License

MIT (subject to change)





