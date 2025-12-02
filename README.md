# EventManagement
EventManagement is a console application for creating, managing, and tracking events. It supports participant management, budget calculation, scheduling, and statistics. Built using arrays, lists, loops, conditionals, methods, and string handling for robust event organization.

# Event Management Console App

A console-based application that allows users to create, manage, monitor, and analyze events.  
Built using basic programming concepts such as arrays, Lists, DateTime, loops, conditions, string processing, and file I/O.

---

## 🚀 Main Features

### 📌 Event Management
- Create, edit, and delete events.
- Check for duplicate names and schedule conflicts.
- Automatically update status based on current time:
  - Planning  
  - Ongoing  
  - Finished  

### 📌 Event Data Includes:
- Event ID (EV-xxx)  
- Name  
- Start / End Date  
- Location  
- Expected participants  
- Budget  
- Status  
- Participant list  

---

## 🧮 Calculations & Statistics
- Total cost and cost by category.
- Average cost per participant.
- Budget overrun alerts.
- Monthly statistics, status-based counts, total event count.
- Simple console bar chart using `*`.

---

## 👥 Participant Management
- Add/remove participants for each event.
- Limit actual participants based on expected capacity.
- Multidimensional array for participant storage.

---

## 📂 Save & Load Data
- Export/import data using CSV or TXT.
- Auto-detection of existing files on startup.
- Uses `;` as field separator and `,` for participant lists.

---

## 📢 Extended Features
- Vendor management and service-cost tracking.
- Simulated notifications for upcoming events.
- Ticket management and revenue calculation.
- Online registration simulation.
- Event report generation in text format.

---

## 🛠 Technologies & Concepts Used
- Conditional structures: `if-else`, `switch-case`
- Loops: `for`, `while`, `foreach`
- One-dimensional and two-dimensional arrays
- List<T>
- DateTime & ParseExact
- String handling (Trim, ToUpper, case-insensitive Contains)
- StreamReader / StreamWriter

---

## ▶️ How to Run
1. Clone the repository:
   ```bash
   git clone <repository-url>
