# Exploratory-Data-Analysis-EDA-Project

🔴 DESCRIPTION 

1. Import Libraries
Python
import pandas as pd
import matplotlib.pyplot as plt
Description:
pandas is used to load and analyze the student dataset.
matplotlib.pyplot is used to create graphs and visualizations.

2. Load the Dataset
Python
df = pd.read_csv("student_performance_sample.csv")
Description:
Reads the CSV file containing student performance data.
Stores the data in a DataFrame named df for analysis.

3. Display the First Five Records
Python
print(df.head())
Description:
Displays the first five rows of the dataset.
Helps verify that the data has been loaded correctly.

4. Generate Statistical Summary
Python
print(df.describe())
Description:
Displays statistical information such as:
Count
Mean
Standard Deviation
Minimum and Maximum values
25%, 50%, and 75% percentiles

5. Create Scatter Plot
Python
plt.scatter(df["Study_Hours"], df["Exam_Score"])
plt.title("Study Hours vs Exam Score")
plt.xlabel("Study Hours")
plt.ylabel("Exam Score")
plt.show()
Description:
Creates a scatter plot showing the relationship between study hours and exam scores.
Helps identify whether students who study more tend to score higher.

6. Create Histogram
Python
plt.hist(df["Exam_Score"], bins=10)
plt.title("Distribution of Exam Scores")
plt.xlabel("Exam Score")
plt.ylabel("Frequency")
plt.show()
Description:
Displays the distribution of students' exam scores.
Shows how many students fall into different score ranges.

🔴 STUDENT PERFORMANCE SAMPLE DATASET

Student_ID,Study_Hours,Attendance,Exam_Score
1,2,61,33
2,4,74,47
3,2,94,38
4,10,87,91
5,1,65,30
6,4,92,69
7,1,95,36
8,9,86,90
9,8,97,87
10,1,70,34
11,6,77,62
12,4,81,49
13,2,84,36
14,6,82,79
15,5,62,60
16,9,67,88
17,2,95,46
18,10,83,100
19,4,64,41
20,4,78,47
21,4,66,53
22,5,89,76
23,6,70,67
24,6,73,65
25,2,98,58
26,3,94,50
27,3,89,54
28,5,100,77
29,4,80,47
30,4,62,49
31,7,77,67
32,4,96,61
33,4,91,61
34,8,69,78
35,3,75,54
36,9,76,97
37,7,97,84
38,6,74,61
39,9,91,86
40,1,67,30
41,3,87,60
42,2,84,45
43,10,89,100
44,5,95,58
45,2,94,44
46,6,67,64
47,7,70,77
48,1,76,39
49,3,92,46
50,5,100,76
51,10,72,89
52,6,70,73
53,9,60,93
54,6,91,63
55,2,83,42
56,4,63,47
57,10,65,84
58,8,64,85
59,3,68,49
60,9,70,85
61,9,98,100
62,4,94,56
63,5,85,74
64,6,88,78
65,8,67,76
66,4,64,50
67,1,97,47
68,4,97,58
69,1,64,39
70,1,74,30
71,1,81,30
72,9,75,87
73,8,73,88
74,3,96,62
75,8,75,87
76,7,72,67
77,2,87,45
78,7,86,83
79,1,66,30
80,7,81,70
81,4,72,49
82,9,88,87
83,7,71,71
84,8,75,74
85,8,95,82
86,1,94,30
87,2,75,35
88,7,91,85
89,4,85,48
90,3,84,40
91,7,76,79
92,5,87,72
93,8,69,76
94,5,73,51
95,10,94,93
96,6,63,55
97,10,90,100
98,9,70,78
99,9,65,80
100,2,98,40

OUTPUT 📌

<img width="1200" height="800" alt="Image" src="https://github.com/user-attachments/assets/a4269463-6c91-4bb0-bffa-ee9be26e8e73" />

<img width="1200" height="800" alt="Image" src="https://github.com/user-attachments/assets/a61e5a7a-00ff-4627-aa19-7e4e021a89e2" />
