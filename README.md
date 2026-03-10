<div align="center">

# 🔒 Password Strength Analyzer

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python&logoColor=white)
![Tkinter](https://img.shields.io/badge/GUI-Tkinter-green?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

> A Python desktop application that analyzes password strength in real time — with a color-coded progress bar, requirement checklist, and actionable feedback to help users build stronger passwords.

</div>

---

## 📸 Overview

This tool evaluates passwords against a comprehensive set of security criteria and provides instant visual feedback as you type. Built with Python's `tkinter`, it's lightweight, dependency-free, and runs on any system with Python installed.

---

## ✨ Features

### 📊 Real-Time Analysis
- Password strength is evaluated **as you type** — no need to click a button
- Instant color-coded feedback on every keystroke

### 🎨 Visual Feedback
- **Color-coded progress bar** — transitions from red → orange → green
- **Strength label** — rates your password as `Very Weak`, `Weak`, `Moderate`, or `Strong`
- **Checkmarks** — each requirement turns green when met

### ✅ Criteria Checked
| Requirement | Bonus Points |
|---|---|
| Minimum 8 characters | ✅ |
| Contains lowercase letters | ✅ |
| Contains uppercase letters | ✅ |
| Contains numbers | ✅ |
| Contains special characters (`!@#$%^&*`) | ✅ |
| 12+ characters | ⭐ Bonus |
| 16+ characters | ⭐ Bonus |

### 💡 Helpful Suggestions
- Provides **specific feedback** on what's missing
- Guides users toward stronger passwords step by step

### 🛠️ User-Friendly Options
- 👁️ Show/hide password toggle
- Clean, modern interface with themed widgets

---

## 🚀 Getting Started

### Prerequisites
- Python 3.x installed
- `tkinter` (included with standard Python installations)

### Installation

```bash
# Clone the repository
git clone https://github.com/sekere01/password-complexity-checker.git

# Navigate into the directory
cd password-complexity-checker

# Run the application
python passchecker.py
```

---

## 📖 Usage

1. **Type your password** into the entry field
2. Watch the **progress bar and strength label** update in real time
3. Check which **requirements are met** in the checklist below
4. Read the **feedback suggestions** to improve your password
5. Toggle **Show Password** to verify what you've typed

---

## 🧠 Strength Scoring

Passwords are scored out of **7 points**:

| Points | Strength | Bar Color |
|---|---|---|
| 0 – 2 | Very Weak | 🔴 Red |
| 3 | Weak | 🔴 Red |
| 4 | Moderate | 🟠 Orange |
| 5 – 7 | Strong | 🟢 Green |

**Scoring breakdown:**
```
+1  At least 8 characters
+1  Contains lowercase letters
+1  Contains uppercase letters
+1  Contains numbers
+1  Contains special characters
+1  Bonus: 12+ characters
+1  Bonus: 16+ characters
```

---

## 📁 Project Structure

```
password-complexity-checker/
│
├── passchecker.py   # Main application file
└── README.md            # Project documentation
```

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to open an issue or submit a pull request.

---

## 📜 Disclaimer

This tool is intended for **educational purposes only**. Always use a reputable password manager for storing and generating passwords in real-world scenarios.
