# 📚 Library Management System (Python)

## 📌 Project Overview
This is a simple **Library Management System** built using Python.  
It allows users to manage book records, issue and return books, and calculate fines for late returns.

The system uses:
- 📖 Dictionary for storing book data
- 💾 JSON file for permanent storage
- 🕒 Date & Time tracking for issue/return
- 💰 Progressive fine calculation

---

## 🚀 Features

### ✅ Book Management
- Display all books
- Show availability status

### ✅ Issue Book
- Enter student name
- Record issue date & time
- Set number of allowed days

### ✅ Return Book
- Shows issue & return date-time
- Checks delay
- Calculates fine automatically

### ✅ Fine System
Fine increases week-wise:

| Week | Fine per Day |
|------|-------------|
| 1st  | ₹10/day     |
| 2nd  | ₹20/day     |
| 3rd  | ₹60/day     |
| 4th  | ₹240/day    |

👉 Formula:
Fine Rate = 10 × (1 × 2 × 3 × ... week number)


---

## 🛠 Technologies Used
- Python 🐍
- JSON (for file storage)
- datetime module

---

## ▶️ How to Run

1. Install Python (if not installed)
2. Download or clone the project
3. Run the file:

## 🖥 Sample Menu


📖 LIBRARY SYSTEM MENU

Show Books
Issue Book
Return Book
Exit

---

## 📊 Example Output

### 📥 Issue Book

✅ Book Issued Successfully!
👤 Student: Rahul
📅 Issue Date & Time: 2026-04-20 14:32:10
⏳ Allowed Days: 5


### 📤 Return Book

📖 RETURN DETAILS
👤 Student: Rahul
📅 Issued On: 2026-04-20 14:32:10
📅 Returned On: 2026-04-28 15:00:00
⚠ Late by 3 days
💰 Fine: 30 Rs


---

## 🧠 Concepts Used
- Dictionary (Data Structure)
- Functions (Modular Programming)
- File Handling (JSON)
- Date & Time Handling
- Loops & Conditions

---

## 🔮 Future Improvements
- 🔍 Search book by name
- ➕ Add/remove books
- 👨‍🎓 Student history tracking
- 🖥 GUI (Tkinter)
- 🌐 Web-based version

---

## 👨‍💻 Author
**Bharat Prajapati**

---

## 📜 License
This project is for educational purposes only.
