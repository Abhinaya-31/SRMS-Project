# 🎓 SRMS – Student Record Management System

SRMS (Student Record Management System) is a C++ Win32 GUI application designed to efficiently manage student academic records and student–admin communication.

The system features a clean, modern graphical interface built using the Win32 API, along with a structured in-memory backend for fast operations — without using any console window.

SRMS provides secure admin login, streamlined student management, and a dedicated student query module. The system automatically updates query status when related student details are modified, ensuring accurate tracking and efficient issue resolution.

---

## ✨ Key Features

### 🔐 Admin Login
- Secure system access  
- Username & password authentication (Admin only)  

---

## 🔑 Default Admin Credentials

Use the following credentials to access the system:

**Username:** `admin`  
**Password:** `1234`

> ⚠️ These credentials are for demonstration purposes only.

---

### 📚 Student Management
- Add new student records  
- Update existing student details  
- Delete student records  
- View all students in a clean tabular format  
- Auto-categorized performance status:
  - Excellent  
  - Very Good  
  - Good  
  - Average  
  - Needs Help  

---

### 🔎 Search Module
- Search by student name  
- Optional auto-add feature if student is not found  

---

### 📝 Student Query Module
- Students can submit queries with ID-based tracking  
- Admin can view all submitted queries  
- Queries automatically marked **Resolved** after updating associated student details  

---

### 🎨 Modern GUI (No Console)
- SRM blue-gradient themed interface  
- Professional Segoe UI font  
- Scrollable data panels  
- Neatly organized layout:
  - Admin Controls  
  - Search Panel  
  - Student Query Panel  
  - Student Records Display  
  - Query Records Display  

---

## ⚙️ Technologies Used

- C++17  
- Win32 API (GUI Programming)  
- MinGW / g++ Compiler  
- GUI-based application (No console window using `-mwindows`)  

---

## 🧩 File Structure

```
srms_gui.cpp
```

Main application source file containing GUI logic and backend record handling.

---

## 🧩 How to Compile

Run the following command in the project directory:

```bash
g++ -std=c++17 srms_gui.cpp -o srms.exe -lgdi32 -luser32 -mwindows
```

---

## ▶️ How to Run

After successful compilation:

```bash
./srms.exe
```

---

## 🎯 Project Objective

SRMS aims to provide a secure, efficient, and user-friendly system for managing student records while improving communication between students and administrators through a structured GUI-based application.

---

**Developed using C++ and Win32 API 🚀**
