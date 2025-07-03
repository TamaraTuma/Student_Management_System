# Student_Management_System
## Objective
The primary objective of this project is to design and create a relational database for a Student Management System (SMS) using SQL. The database will efficiently store and manage data on students, courses, instructors, and enrollments, enabling users to perform key administrative functions such as adding students, assigning courses, and generating dynamic reports through SQL queries.

## Tables to be Created
1.	Students (StudentID, Name, Gender, DOB, DepartmentID)
2.	Departments (DepartmentID, DepartmentName)
3.	Courses (CourseID, CourseName, DepartmentID)
4.	Enrolments (EnrollmentID, StudentID, CourseID, EnrollmentDate)
5.	Instructors (provide relevant columns in relation to your tables)
(InstructorID, Name, DepartmentID, Gender)

## Relationships 
- One Department has many Students
- One Department offers many Courses
- One Student can enroll in many Courses (many-to-many via Enrollments)

## Entity Relationship Diagram 
![]()
