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

### A. Home Screen
- Title and current budget display
- Budget input field and save button
- Button to create a new grocery list
- Progress bar showing remaining budget

### B. Create List Screen
- Fields to enter item name and price
- Button to add the item to the list
- ListView displaying all items
- Progress bar tracking total spent vs budget
- TextView showing updated budget status

*Note: Wireframes were built and revised using Figma and referenced during layout development.*

## VII. Innovation
Unlike complex financial tools, Grocery Budget Helper focuses on ease of use and budget tracking for a specific task: grocery shopping. It empowers users to take immediate financial action without requiring an internet connection or login credentials.

## VIII. Changelog

### Version 1.0.0 – Initial Release
- Home screen with budget input and display
- Navigation to Create List activity
- Ability to enter item names and prices
- Dynamic ListView showing entered items
- SharedPreferences implementation for budget persistence
- Basic progress bar reflecting budget use

### Version 1.1.0 – UI Enhancements & Fixes
- Budget dynamically updates on Home screen
- Error handling for empty item inputs
- Cleaned redundant code and improved formatting
- Added input validation and user feedback
- Reorganized layout with padding and spacing fixes

### Version 1.2.0 – Final Polish
- Added functionality for budget progress calculation
- Progress bar logic connected to total item costs
- Enhanced user flow between screens
- Added app icon and metadata for release

## IX. Reflection

The development of Grocery Budget Helper taught me valuable lessons about mobile UI/UX, user data persistence, and structured project development in Android Studio. Initially, the challenge was linking user input to dynamic data updates across activities. Through trial and error, I learned how to use `SharedPreferences` for storing budgets and manage UI states with Kotlin. Debugging crashes during navigation taught me the importance of clean manifest declarations and consistent ID matching across XML and Kotlin files. 

This app represents my growth in developing functional, user-friendly mobile apps with a focus on practical problem-solving. If given more time, I would extend the app to include:
- Notifications for approaching budget limits
- History tracking of past grocery trips
- Dark mode and accessibility options

