# 🍔 Campus Food Delivery Platform
[![Portfolio](https://img.shields.io/badge/krisgarg.in-Portfolio-0A0A0A?style=for-the-badge&logo=google-chrome&logoColor=white)](https://krisgarg.in)
<p align="center">
  <img src="https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React Native"/>
  <img src="https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white" alt="Expo"/>
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React"/>
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" alt="Firebase"/>
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript"/>
</p>

<p align="center">
  A complete food delivery ecosystem for campus communities featuring a <strong>Mobile App for Students</strong> and a <strong>Web Dashboard for Vendors</strong>.
</p>

---

## 📦 What's Inside?

| Application | Description | Technology |
|------------|-------------|------------|
| **📱 Student Mobile App** | Order food, track deliveries, rate vendors | React Native + Expo |
| **🖥️ Vendor Dashboard** | Manage menu, accept orders, view analytics | React.js + Vite + Tailwind |

---

## ✨ Features

### 📱 Student Mobile App
- **🔍 Smart Discovery** - Browse restaurants with category filters (Breakfast, Main Course, Snacks, Beverages, Desserts)
- **🛒 Seamless Ordering** - Add items to cart, adjust quantities, and view detailed bill breakdown
- **📱 Live Tracking** - Real-time order status updates from Received → Preparing → Ready → Completed
- **⭐ Rate & Review** - Submit ratings that instantly update vendor scores
- **🔔 Push Notifications** - Get notified when your order is ready or declined
- **🤖 AI Assistant** - Chat with AI for food recommendations and queries
- **❤️ Favorites** - Save and quickly reorder from your favorite restaurants
- **📍 Location-Based** - Deliver to specific campus hostels and blocks

### 🖥️ Vendor Dashboard
- **📊 Live Analytics** - Real-time overview of orders, revenue, and customer ratings
- **🍽️ Menu Management** - Easily add, edit, or remove menu items with images
- **📦 Order Control** - Accept, reject, and update order status in real-time
- **🔔 Instant Alerts** - Get notified immediately when new orders arrive
- **📈 Performance Insights** - Track sales trends, popular items, and peak hours
- **🎨 Brand Management** - Customize restaurant profile, categories, and availability status
- **⚡ Bulk Actions** - Quick filters, search, and multi-order status updates

---

## 🛠️ Built With

**Mobile App:** React Native · Expo SDK 52 · TypeScript · Expo Router  
**Dashboard:** React 18 · Vite · TypeScript · Tailwind CSS · Recharts  
**Backend:** Firebase Firestore · Firebase Auth · Firebase Storage · Cloud Messaging

---

## 📸 Screenshots

> Add your app and dashboard screenshots here

---

## 🚀 Getting Started

### Prerequisites
- Node.js (v18+)
- npm or yarn
- Expo CLI
- Firebase account
- Android/iOS device or emulator

### Installation

**Mobile App:**
Navigate to the `app` folder, install dependencies, configure Firebase, and start the Expo development server.

**Vendor Dashboard:**
Navigate to the `vendor-dashboard` folder, install dependencies, configure Firebase, and start the Vite development server.

**Firebase Setup:**
Create a Firebase project, enable Authentication, create a Firestore database, enable Cloud Messaging, and add your configuration to both applications.

---

## 🔥 Key Highlights

### Real-Time Synchronization
Both the mobile app and dashboard connect to the same Firebase Firestore database, ensuring instant updates across all devices.

### Dynamic Rating System
When students submit ratings, vendor scores are automatically recalculated and updated in real-time using Firebase transactions.

### Push Notifications
Students receive instant notifications when their order status changes to Ready or Declined. Requires a physical device for testing.

### Smart Filtering
Restaurants can be filtered by food categories, making it easy for students to find exactly what they're craving.

---

## 📱 Building for Production

### Mobile App
Use Expo Application Services (EAS) to build standalone APK or IPA files for distribution.

### Vendor Dashboard
Build the production bundle and deploy to Firebase Hosting, Vercel, Netlify, or any static hosting service.

---

## 🤝 Contributing

Contributions are welcome! Fork the repository, create a feature branch, commit your changes, and open a pull request.

---

## 📄 License

This project is licensed under the MIT License. See the LICENSE file for details.

---

## 👨‍💻 Author

**Your Name**  
GitHub: [@krisgarg25](https://github.com/krisgarg25)  
Email: krisgarg25@gmail.com

---

## 🙏 Acknowledgments

Special thanks to Expo, Firebase, React, Tailwind CSS, and the open-source community for making this project possible.

---

<p align="center">
  <strong>Made with ❤️ for Campus Communities</strong><br>
  🍕 Bringing delicious food closer to students, one order at a time
</p>
