
# Student Management System

## Overview

The Student Management System is a Python-based application designed to manage student records efficiently. It provides functionalities for adding students, enrolling them in courses, managing attendance, calculating average grades, and searching for student information. This project serves as an excellent demonstration of Object-Oriented Programming (OOP) principles, including encapsulation, inheritance, polymorphism, and abstraction.

## Features

- **Add Student**: Easily add new student records to the system with unique IDs and names.
- **Enroll in Courses**: Enroll students in various courses, managing their course load.
- **Manage Attendance**: Mark and track attendance for each student in their enrolled courses.
- **Calculate Average Grades**: Compute the average grades for students, helping to assess their academic performance.
- **Search for Students**: Quickly search for student records by name or ID to retrieve relevant information.
- **Display Student Information**: Show detailed information for each student, including enrolled courses and attendance records.

## Technologies Used

- **Python**: The programming language used to develop the system.
- **Object-Oriented Programming**: The project demonstrates OOP concepts such as encapsulation, inheritance, polymorphism, and abstraction.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/student-management-system.git
   ```

2. Navigate to the project directory:
   ```bash
   cd student-management-system
   ```

3. Run the main script:
   ```bash
   python main.py
   ```

## Usage

1. Add students to the system.
2. Enroll them in courses.
3. Manage their attendance by marking days as present or absent.
4. Calculate and display the average grades for each student.
5. Search for students by their name or ID.

## Example

```python
# Create a new school
school = School("ABC Academy", "New York")

# Create courses
course1 = Course("CS101", "Introduction to Computer Science")
course2 = Course("MATH101", "Calculus I")

# Add courses to the school
school.add_course(course1)
school.add_course(course2)

# Add students
student1 = Student("001", "Alice")
student1.enroll(course1)
student1.add_grade(course1, 90)

# Mark attendance
student1.mark_attendance(course1, "2024-10-01", present=True)

# Search for students
print(school.search_student("Alice"))
```

## Contribution

Contributions are welcome! If you have suggestions for improvements or new features, feel free to fork the repository and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

