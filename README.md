# 🔐 Random Password Generator with PyQt5

A GUI-based random password generator built using **Python** and **PyQt5**

---

## 📌 Features

- **User Login & Sign-Up**  
  Secure authentication with form validation and Firebase as the backend.

- **Password Generation Options**
  - Generate passwords based on selected character sets:
    - Alphabets (uppercase, lowercase, or both)
    - Numbers
    - Special characters
  - Option to exclude specific characters
  - Choose between:
    - **Random Passwords**: Purely randomized
    - **Pronounceable Passwords**: Alternates between consonants and vowels, optionally mixes in numbers/symbols

- **Advanced Options**
  - Toggle advanced settings panel
  - Save generated passwords under user accounts
  - Prevent reuse of previously generated passwords

- **User-Friendly Interface**
  - Intuitive layout built with PyQt5
  - Dynamic visibility of form elements (e.g., character case dropdown)
  - Real-time validation and warnings

---

## 🛠 Technologies Used

- Python 3.x
- PyQt5 (for GUI)
- Firebase Realtime Database (for user data storage)
- `requests`, `random`, `string`, `re` libraries

---

## 📷 UI Overview

- **Login/Signup Page**
- **Password Generation Panel**
- **Advanced Settings Toggle**
- **Password Display Section**

---

## 🚀 How It Works

1. **Login or Sign Up** to access advanced features.
2. **Select your preferred character sets**, and exclude any characters if needed.
3. Choose **password type** (random or pronounceable).
4. Click **Generate Password** to get a secure password.
5. (Optional) If logged in and advanced options are enabled, the password is saved to Firebase unless it's a duplicate.

---
