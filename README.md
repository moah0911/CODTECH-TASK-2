# CODTECH-TASK-2
Overview of Student Grade Manager Program
This Python program implements a Student Grade Manager that allows users to track and manage student grades across multiple subjects. It provides functionality to add grades, calculate averages, assign letter grades, calculate GPA, and display a summary of all grades and statistics. The program operates through a simple text-based interface and uses a class to manage the data.

Key Features:
Add Grades: Users can input grades for different subjects. If a grade for a subject already exists, the new grade is added to the list of grades for that subject.
Calculate Average: The program calculates the overall average across all subjects and grades.
Letter Grade Calculation: Based on the average grade, a corresponding letter grade is determined (A, B, C, D, or F).
GPA Calculation: A GPA is calculated based on the average grade using a predefined scale.
Display Grades and Summary: Users can view the grades entered for each subject and get a summary, including the average, letter grade, and GPA.
Error Handling: It checks that the entered grades are valid numbers and within the acceptable range (0-100).
Class Structure:
StudentGradeManager: Contains methods for adding grades, calculating averages, letter grades, GPA, and displaying grades and summaries.
add_grade(subject, grade): Adds a grade to a specified subject.
calculate_average(): Calculates the average grade across all subjects.
get_letter_grade(average): Determines the letter grade based on the average.
calculate_gpa(average): Converts the average grade to a GPA score.
display_grades(): Displays the grades for each subject.
display_summary(): Displays the grades, overall average, letter grade, and GPA.
Example Use Case:
Add grades for subjects (e.g., Math, Science, History).
Calculate the overall average and determine the corresponding letter grade and GPA.
View all entered grades and the detailed summary of the student's performance.
This program is useful for managing academic performance, providing a structured way to track and evaluate grades and GPA.
