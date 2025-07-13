# Crypto Price Tracker App – Project Outline

---

## I. Project Description

### A. Overview
1. **Name:** Crypto Price Tracker
2. **Purpose:** Deliver real-time pricing, charts, watchlists, and daily summaries for top cryptocurrencies

### B. Objectives
1. Provide accurate, up-to-date market data
2. Enable quick portfolio snapshots and alerts
3. Maintain a lightweight, responsive UI

### C. Scope
1. Support for major coins (BTC, ETH, etc.)
2. Core features only—no trading execution

---

## II. Problem Addressing

### A. Market Need
1. Students and casual investors lack a simple mobile tool to monitor prices
2. Existing apps are either too complex or too expensive

### B. Target Users
1. Crypto-curious students
2. Beginner traders seeking an easy reference

### C. Pain Points
1. Overwhelming interfaces
2. Delayed price updates
3. No lightweight watchlist or alert system

---

## III. Platform

### A. Mobile Operating Systems
1. iOS
2. Android

### B. Cross-Platform Framework
1. React Native (preferred)
2. Alternative: Flutter or Vue Native

### C. Deployment Targets
1. App Store (iOS)
2. Google Play (Android)

---

## IV. Front/Back End Support

### A. Frontend
1. **Framework:** React Native
2. **State Management:** Redux or Context API
3. **UI Library:** NativeBase or React Native Paper

### B. Backend
1. **Runtime:** Node.js with Express
2. **API Integration:** CoinGecko (public REST endpoints)
3. **Database:** MongoDB Atlas for user watchlists and settings
4. **Authentication:** JWT + bcrypt (optional for personalized features)

---

## V. Functionality

### A. Real-Time Price Feed
1. Polling interval and data caching
2. Error handling and offline fallback

### B. Watchlist Management
1. Add/remove coins
2. Persisted per user (if authenticated) or locally

### C. Price Charts
1. Simple line graphs (24h / 7d / 30d)
2. Zoom and pan support

### D. Daily High/Low Summaries
1. Highlight price extremes
2. Show percentage change

### E. Alerts & Notifications (stretch)
1. Threshold-based push alerts
2. In-app notification center

---

## VI. Design (Wireframes)

### A. Home Screen
1. List of tracked coins, current price, and 24h change
2. “Add Coin” floating action button

### B. Coin Detail Screen
1. Price chart component
2. High/low stats and market cap
3. Alert toggle and threshold input

### C. Watchlist Screen
1. Segmented control: “All” vs. “My Watchlist”
2. Bulk remove/edit actions

### D. Settings Screen
1. Theme toggle (light/dark)
2. Polling interval selector
3. Notification preferences

---
