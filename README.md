# Sneakers Shopping App (Flutter UI Prototype)

A simple **Sneakers Shopping App UI** built using **Flutter** and **Dart**.  
This project was created while learning Flutter, focusing on **UI design, layout structure, and navigation**.  
All product data and images are **hardcoded**, with no backend or API integration.

---

## 🧭 Overview

The **Sneakers Shopping App** is a front-end prototype that simulates a basic e-commerce experience:

- Browse a list of sneaker products  
- View product details with images, name, price, and description  
- Navigate smoothly between screens  
- Designed for learning purposes and UI practice  

The goal of this project was to **practice Flutter widgets, layouts, and state management basics**.

---

## ✨ Features

- Clean and minimal **shopping app UI**  
- Home screen with **product grid**  
- Product details screen with **images and info**  
- Smooth **screen navigation**  
- Responsive layout for **different screen sizes**  
- **No backend** — all data is static/hardcoded  

---

## 🧰 Tech Stack

| Layer | Technology |
|-------|-------------|
| Framework | Flutter |
| Language | Dart |
| UI Components | Flutter Widgets (Container, GridView, ListView, etc.) |
| State Management | setState() / basic widget control |
| Assets | Hardcoded images |
| Platform | Android / iOS |

---

## ⚙️ Setup / Installation

To run this app locally:

```bash
# Clone the repository
git clone https://github.com/nish13nt/Sneakers-Shopping-App.git
cd Sneakers-Shopping-App

# Install dependencies
flutter pub get

# Run the app
flutter run



lib/
├── main.dart                 # Entry point
├── screens/
│   ├── home_screen.dart      # Home / product list
│   └── product_detail.dart   # Product details page
├── widgets/
│   ├── product_card.dart     # Custom UI card for products
│   └── custom_appbar.dart
└── data/
    └── products.dart         # Hardcoded product info and images
