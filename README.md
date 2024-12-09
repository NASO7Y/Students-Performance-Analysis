# Students-Performance-Analysis
This project analyzes student performance data across subjects (Algebra, Programming, Physics) using various data manipulation techniques. The dataset is processed, scores are categorized into grades (A, B, C, D, F), and visualizations such as bar charts and pie charts are created to showcase trends and comparisons between subjects.

This project involves analyzing a dataset of student performance across three subjects: Algebra, Programming, and Physics. The dataset (StudentsPerformance.csv) is processed and analyzed to gain insights into student performance and categorize their scores into grades (A, B, C, D, F).

Key Steps:

Data Preprocessing:

The dataset is loaded and the "ID" column is added to uniquely identify each student.
Scores for each subject are classified into grades using a custom function. Grades are assigned based on the following score ranges:
A for scores above 85
B for scores between 75 and 85
C for scores between 65 and 75
D for scores between 50 and 65
F for scores below 50
Sorting and Ranking:

Students are sorted based on their scores in each subject. The top 5 students for each subject are identified.
A total score for each student is computed by summing their scores across the three subjects.
Visualization:

A variety of visualizations are created to show trends in student performance:
Bar charts to display the total grades of students.
Pie charts to visualize the distribution of grades (A, B, C, D, F) for each subject (Math, Programming, and Physics).
Line plots to show the relationship between subject scores and grade categories.
Insights:

The project also provides insights into the grade distribution across the subjects. It prints the total number of students in each grade category for Algebra, Programming, and Physics.
The project showcases the importance of data preprocessing and visualizations to better understand and interpret student performance.
