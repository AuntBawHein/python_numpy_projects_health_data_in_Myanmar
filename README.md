# python_numpy_projects_health_data_in_Myanmar

                   Title of the report
Report title: Health data Burmese people from 2020 to 2023.
NumPy in Python programming Language. 

Introduction: 
This report is about NumPy, which is a library used for working with arrays and mathematical operators in Python.

Advantages:
It helps us work with numbers in a special way and create different shapes and solve the problem with its method.

What to use:
We can use it to do a large collection of numbers and solves mathematics problems very fast.

When to use it ? :
We use it when we want to deal with lots of numbers, especially mathematics.

Why do we use Numpy in Python?:
Because it can help us work with numbers, slicing and calculating the numbers.










# This is the code that I did
import numpy as np
import matplotlib.pyplot as plt

# Health data for Burmese people from 2020 to 2023
years = np.array([2020, 2021, 2022, 2023])
cases = np.array([500, 600, 800, 700])
ages = np.array([45, 50, 42, 55])
scores = np.array([7, 6, 8, 5])

# Display the health data for each year
for year, case, age, score in zip(years, cases, ages, scores):
    print(f"Year: {year}, Cases: {case}, Average Age: {age}, Average Score: {score}")

# Create a line graph with bubbles
plt.figure(figsize=(10, 6))
plt.plot(years, cases, marker='o', label='Cases')
plt.scatter(years, cases, s=ages * 5, c='blue', alpha=0.5, label='Age Bubble')
plt.scatter(years, cases, s=scores * 15, c='green', alpha=0.5, label='Score Bubble')
plt.xlabel("Year")
plt.ylabel("Cases")
plt.title("Health Data for Burmese People (2020-2023)")
plt.legend()
plt.grid(True)
plt.show()





# These are the output
Year: 2020, Cases: 500, Average Age: 45, Average Score: 7
Year: 2021, Cases: 600, Average Age: 50, Average Score: 6
Year: 2022, Cases: 800, Average Age: 42, Average Score: 8
Year: 2023, Cases: 700, Average Age: 55, Average Score: 5


Seperate questions and images 
[Questions for Numpy Health data for Burmese people from 2020 to 2023.docx](https://github.com/AuntBawHein/python_numpy_projects_health_data_in_Myanmar/files/13692130/Questions.for.Numpy.Health.data.for.Burmese.people.from.2020.to.2023.docx)
         
 This is the project that I made.
1.	What type of information is being discussed in this code?
= The code is about Health Data of Burmese people, cases, ages and scores.

2.	For which specific years is the data being collected in this code?
= 2020, 2021, 2022, 2023

3.	Can you tell me how many cases were recorded in the year 2021?
= 600 cases were recorded in the year 2021.

4.	What was the average age of the people in the year 2022?
= In the year 2022 was 42 years old.

5.	What do the blue bubbles on the graph represent?
= About the average age of people for each year 

6.	How can we see the changes in the number of cases over the years on the graph?
= The graph’s line and the position of the dots show how cases changed over years.

7.	 What does the title of the graph tells us?
= It tells us about health data for Burmese people since 2020 to 2023.

8.	 What information do the green bubbles show?
= The bigger green bubbles on the graph means that the scores are higher.

9.	Can you explain how the size of the bubbles on the graph is related to the data?
=  Big bubbles represent higher values like ages, or scores, helping us compare the data.

These are our image diagram here sir.
![diagram_image_numpy](https://github.com/AuntBawHein/python_numpy_projects_health_data_in_Myanmar/assets/150255399/6b7c87bb-c155-4183-aec5-cdbd80fbb768)



These are all the codes sir, thank you very much.
[reports_numpy_python (1).docx](https://github.com/AuntBawHein/python_numpy_projects_health_data_in_Myanmar/files/13692131/reports_numpy_python.1.docx)

This is my first project of Python programming language and this is my first time using Github to upload the project sir.






