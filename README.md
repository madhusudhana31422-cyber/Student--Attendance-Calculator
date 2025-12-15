# Student--Attendance-Calculator
📊 Attendance Tracker using Python

🔹 Project Overview

This is a simple Python beginner project that calculates a student's attendance percentage and checks whether the student is eligible for the exam based on attendance criteria.


---

🔹 Features

Takes total number of classes as input

Takes attended classes as input

Calculates attendance percentage

Displays eligibility result (Eligible / Not Eligible)

Beginner-friendly and easy to understand



---

🔹 Attendance Rule

✅ 75% or above → Eligible for Exam

❌ Below 75% → Not Eligible for Exam



---

🔹 Python Code

# Attendance Tracker#Attendence Tracker
Total_Classes=int(input("Enter Total Number of classes:"))
Attended_Classes=int(input("Enter Number of Classes attended:"))

print("Calculation:-")
Attendance=Attended_Classes/Total_Classes*100
print(f"Attendance:{Attendance:.2f}%")

if Attendance>=75:
    print("Eligible For Exam.")
else:
    print("Not Eligible.")


---

🔹 Sample Output

Enter total number of classes: 100
Enter number of classes attended: 80
Calculation:
Attendance: 80.00%
Eligible for Exam.


---

🔹 Skills Used

Python basics

Input & Output

Conditional statements

Percentage calculation



---

🔹 Author

Madhusudhana R


