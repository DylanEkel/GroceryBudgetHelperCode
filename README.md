# 🛒 Grocery Budget Helper

**Grocery Budget Helper** is an Android application designed to help users track and manage their grocery expenses effectively. The app allows users to set a custom grocery budget, create shopping lists, add items with associated costs, and monitor their spending in real time with a progress bar.

## 📱 Project Description

This app was developed as a term project for the Mobile Application Development course (COM-437). It provides users with a simple, intuitive interface to manage their grocery expenses and ensure they stay within budget.

## 🧩 Problem Addressed

Grocery shopping can often lead to overspending if not properly managed. Many users need a quick and simple way to:
- Set a grocery budget.
- Add and track items during shopping.
- Visually see how much of their budget they’ve used.

## 🧠 Platform

- **Operating System:** Android (tested on Android 9 and later)
- **Language:** Kotlin
- **IDE:** Android Studio
- **Minimum SDK:** 24 (Android 7.0)

## 🛠️ Frontend / Backend Support

- **Frontend:** XML layouts with LinearLayouts and ConstraintLayouts, buttons, text fields, and progress bars.
- **Backend:** Kotlin code using SharedPreferences for saving budget and item data locally.

## ✅ Functionality

- Set and save a custom grocery budget.
- Create new shopping lists.
- Add items with names and prices.
- Automatically update the progress bar to show total spending relative to the budget.
- Simple two-activity navigation (Home and Create List).
- Data persistence using SharedPreferences.

## 🎨 Design (Wireframes)

Wireframes were used during early planning to ensure intuitive layout:
- **Home Screen:** Displays title, current budget, and a button to create a new list.
- **Create List Screen:** Allows entry of item names and costs; updates the progress bar as items are added.

*Note: Wireframes were built and revised using Figma and referenced during layout development.*

## 🔧 How to Install

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/GroceryBudgetHelper.git
