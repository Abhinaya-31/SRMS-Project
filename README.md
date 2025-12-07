SRMS: Student Record Management System
The Student Record Management System (SRMS) is a C++ Win32 GUI application designed to efficiently manage student academic data and student–admin communication. 
The project provides a clean, modern interface built using the Win32 API, along with a structured in-memory backend to perform fast operations without console windows.
SRMS includes secure admin login, streamlined student management, and a dedicated module for student queries.
The system automatically updates query status when related student details are modified, ensuring accurate tracking and easy handling of student concerns.

 Key Features:
 🔐 Admin Login
Secure access to the system
Username & password authentication (admin only)
📚 Student Management
Add new student records
Update existing student details
Delete student records
View all students in a clean tabular format
Auto-categorized performance status (Excellent / Very Good / Good / Average / Needs Help)
🔎 Search Module
Search by student name
Auto-add student if not found (optional feature)
📝 Student Query Module
Students can submit queries with ID-based tracking
Admin can view all submitted queries
Queries automatically marked Resolved after updating associated student details
🎨 Modern GUI (No Console)
SRM blue-gradient themed GUI
Segoe UI font for professional appearance
Scrollable data panels
Neatly arranged sections:
Admin Controls, Search Panel, Student Query Panel, Student Records & Query Records display.

⚙️ Technologies Used
C++17
Win32 API (GUI Programming)
MinGW / g++ Compiler
No console window — GUI only

🧩 How to Compile
Run this command in the terminal:
g++ -std=c++17 src/srms_gui.cpp -o srms.exe -lgdi32 -luser32 -mwindows

▶️ How to Run
After successful compilation:
./srms.exe

