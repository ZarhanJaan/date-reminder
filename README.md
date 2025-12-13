# 📅 Calendar Reminder App (Python + Tkinter)

A desktop calendar application built with **Python** and **Tkinter** that allows users to mark dates and attach reminders. Reminders are stored persistently in a local JSON file (`remind.json`).

---

## 📖 Description

This project provides a simple interactive calendar with reminder functionality.  
Users can navigate between months, mark specific dates, add reminders, and preview all reminders for the current month.  
Data is saved locally in JSON format, ensuring reminders are preserved between sessions.

---

## ✨ Features

- 📅 Interactive monthly calendar view  
- ➕ Add reminders by clicking on a date  
- 🗑️ Remove reminders by clicking again on a marked date  
- 👀 Right‑click on a date to view its reminder  
- 🔎 Preview all reminders for the current month  
- 💾 Persistent storage in `remind.json`  

---

## 🛠️ Tech Stack

- **Language:** Python 3  
- **GUI Framework:** Tkinter (with ttk widgets)  
- **Storage:** JSON file (`remind.json`)  
- **Libraries:**  
  - `tkinter` (GUI)  
  - `calendar` (calendar generation)  
  - `datetime` (date handling)  
  - `json` & `os` (data persistence)  

---

## ⚙️ Installation & Setup

### 1. Clone Repository
```bash
git clone https://github.com/username/calendar-reminder-app.git
cd calendar-reminder-app
