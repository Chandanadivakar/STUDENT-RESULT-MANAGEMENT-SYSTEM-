# STUDENT-RESULT-MANAGEMENT-SYSTEM-
To modernize the traditional paper-based result process, we have developed a Student Result Management System (SRMS) — a web application that enables students to conveniently view their academic results online.

This system is built using Python with the Flask framework, and stores student data and results in a lightweight SQLite database.

Key Functionality:

Students access their results by visiting the SRMS website, where they are prompted to log in by entering:
	•	Their USN (University Seat Number),
	•	Date of Birth (used as the password),
	•	A CAPTCHA code for security verification.

Once authenticated, students can view their detailed academic performance, including:
	•	Subject-wise marks,
	•	Both internal assessments and external exam scores,
	•	Overall total marks and corresponding grades.

Technology Used:
	•	Frontend: Designed with HTML, CSS, and Bootstrap to ensure a clean and responsive user interface.
	•	Backend: Developed using Python (Flask) for handling server-side logic and data processing.
	•	Database: SQLite is used for storing student records and results efficiently.
	•	Security Measures: CAPTCHA-based human verification and DOB authentication provide an extra layer of security to protect student data.
