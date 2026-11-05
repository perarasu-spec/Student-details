# Student-details
🎓 Student Information & Record Management System

A responsive, feature-rich web application built with HTML5, CSS3, and JavaScript for collecting, managing, and storing student records locally in your browser.

🌟 Features Included
1. 📋 Comprehensive Student Details Collection
Basic Details: Full Name, Roll / Registration Number (unique check), Date of Birth, Gender, Email Address, Contact Number, Department / Major, and Current Semester.
Family & Guardian Details: Father's Name, Contact & Occupation, Mother's Name, Contact & Occupation, Guardian/Emergency Contact Name & Phone, and Permanent Residential Address.
Attendance Percentage Tracking:
Automatically calculates attendance percentage from Total Classes Scheduled and Classes Attended.
Manual override support for typing direct percentage.
Color-coded attendance status pills:
🟢 Good Standing: Attendance ≥ 75%
🟡 Warning: 60% – 74.9%
🔴 Critical Attendance Alert: < 60%
Semester Marks & Subject Grading:
Dynamically add or remove semester subjects.
Enter Max Marks and Marks Scored per subject.
Instant grade badge calculation (A+, A, B, C, D, F) per subject.
Real-time overall semester score calculation: Total Scored, Semester Percentage, and Academic Standing (Distinction, First Class, Second Class, Pass, Fail).
2. 💾 Persistent Browser Storage & Management
Local Storage Integration: All records are saved in browser localStorage, meaning data persists across page refreshes and browser restarts.
Student Profile Directory: Interactive cards showcasing student summary, attendance status, and semester percentage.
Search & Filter:
Search by Name, Roll Number, or Email address in real time.
Filter by Department.
Detailed Student Profile View Modal:
Comprehensive view of student's personal, family, attendance, and subject marks report.
🖨️ Print Report Card: Direct print/PDF export styling for student report cards.
✏️ Edit & Update: Modify any student information without losing existing records.
🗑️ Delete & Clear All: Safe deletion with user confirmation alerts.
📥 CSV Export: Export all student records into a downloadable spreadsheet file (.csv).
✨ Sample Data Loader: One-click demo dataset generation to preview the system immediately.
🚀 How to Run the App

Directly in your browser:

Navigate to the project folder: C:\Users\perar\.gemini\antigravity\scratch\student-record-app\
Double click index.html (or right-click -> Open with Chrome / Edge / Firefox).

Using a local server (Optional): If you have Python installed, you can open PowerShell in this folder and run:

powershell
python -m http.server 8000python -m http.server 8000

Then open http://localhost:8000 in your web browser.

📂 File Structure
student-record-app/
├── index.html     # Semantic UI layout, forms, tabs, directory grid, and modal
├── style.css      # Modern design system, responsive layout, animations, print media rules
├── app.js         # State management, calculations, local storage, validation, CSV export
└── README.md      # Documentati
