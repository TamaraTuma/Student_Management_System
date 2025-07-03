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
![](SMS_schema.png)


## Entities (Tables)
1.	Students
Primary Key: StudentID 
Fields: Name, Gender, Date of Birth (DOB), DepartmentID 
Purpose: Contains details about each student and links them to a specific department. 

2.	Departments
Primary Key: DepartmentID 
Fields: DepartmentName 
Purpose: Holds information about various departments within the institution. 

3.	Courses
Primary Key: CourseID 
Fields: CourseName, DepartmentID 
Purpose: Stores details of courses, with each course associated with one department. 

4.	Enrollments
Primary Key: EnrollmentID 
Fields: StudentID, CourseID, EnrollmentDate 
Purpose: Records which students are enrolled in which courses and when, representing the many-to-many relationship between students and courses. 

5.	Instructors
Primary Key: InstructorID 
Fields: Name, Gender, DOB, DepartmentID, Phone 
Purpose: Maintains instructor information, with each instructor linked to a department. 


