Student Class
	•	Encapsulates student data: roll number, name, and marks.
	•	Methods:
	•	average() → computes mean score.
	•	grade() → assigns grade A-F based on average.
	•	status() → pass if average ≥ 50 else fail.
	•	_str_() → converts object into a storable string for the file.
	•	from_string() → static method to convert back from file line to Student object.

⸻

File Handling
	•	Data stored in a plain text file (students.txt).
	•	Each student written as roll_no,name,marks.
	•	Functions:
	•	save_student(student) → appends student to file.
	•	load_students() → reads file and rebuilds Student objects.

⸻

Features
	1.	Add Student → Input roll no, name, marks; saves to file.
	2.	Display Students → Loads all from file and shows roll no, name, average, grade, status.
	3.	Search Student → Finds student by roll number.
	4.	Generate Report → Shows totals, passed/failed, class average.

⸻

Main Menu
	•	Interactive loop allows repeated actions.
	•	Ensures project behaves like a real application.
	•	Combines OOP, file handling, input validation, reporting into one.
