# Python Projects

## Student Marks Data Analysis and Visualisation
This project demonstrates how Python can be used to analyse and visualise student performance data. Using a dataset containing student marks, I performed exploratory data analysis (EDA), generated descriptive statistics, and created a range of visualisations to identify trends and compare student performance across classes and genders

# Visualisations Created
I used the student.csv dataset to create various charts with Matplotlib and Seaborn, illustrating mark distributions, class sizes, and student performance by gender.

- Histogram showing the distribution of student marks.
```python
plt.figure(figsize=(10, 6))
plt.hist(df['mark'], bins=10, edgecolor='black')
plt.title('Distribution of Marks')
plt.xlabel('Marks')
plt.ylabel('Frequency')
plt.show()
```


- <img width="981" height="638" alt="image" src="https://github.com/user-attachments/assets/66bd5751-5c9a-4f44-9859-2b512387d36f" />
I created a histogram using Matplotlib to visualise the distribution of student marks. I divided the marks into 10 intervals (bins) to show how frequently scores occurred across different ranges.
The histogram made it easy to identify the overall distribution of marks, showing where most students' scores were concentrated and highlighting any patterns or variations in the data.

- Scatter plot comparing marks by gender.
```python
df['gender'] = df['gender'].astype(str)
plt.figure(figsize=(10, 6))
plt.scatter(df['gender'], df['mark'], alpha=0.7)
plt.title('Marks by Gender')
plt.xlabel('Gender')
plt.ylabel('Marks')
plt.show()
```

- <img width="981" height="638" alt="image" src="https://github.com/user-attachments/assets/924b7db9-48d7-47bb-bb46-a952298f5bf8" />
I created a scatter plot using Matplotlib to compare student marks by gender. I first converted the gender column to a string data type and then plotted gender on the x-axis and marks on the y-axis.
The scatter plot made it easy to compare the distribution of marks between male and female students and identify any differences or patterns in their performance.

- Box plot showing marks by class.
```python
plt.figure(figsize=(10, 6))
sns.boxplot(x='class', y='mark', data=df)
plt.title('Marks Distribution by Class')
plt.xlabel('Class')
plt.ylabel('Marks')
plt.show()
```

- <img width="981" height="638" alt="image" src="https://github.com/user-attachments/assets/cb459edb-e904-45b0-935a-b460f4b17f07" />
I created a box plot to compare the distribution of student marks across different classes. I plotted class on the x-axis and marks on the y-axis to visualise the spread of marks for each class.
The box plot made it easy to compare the distribution of marks between classes, showing the median, spread of scores, and any potential outliers. It helped identify differences in student performance across the classes.

- Count plot showing the number of students in each class.
```python
plt.figure(figsize=(10, 6))
sns.countplot(x='class', data=df)
plt.title('Number of Students in Each Class')
plt.xlabel('Class')
plt.ylabel('Number of Students')
plt.show()
```

- <img width="981" height="638" alt="image" src="https://github.com/user-attachments/assets/88228f7b-577a-4137-8373-d02c58611ef9" />
I created a count plot using Seaborn to display the number of students in each class. I plotted the class column on the x-axis and the count of students on the y-axis.
The count plot showed the number of students in each class, making it easy to compare class sizes and identify which classes had the highest and lowest number of students.

- Bar chart displaying the average marks by gender.

```python
plt.figure(figsize=(10, 6))
avg_marks_gender = df.groupby('gender')['mark'].mean().reset_index()
sns.barplot(x='gender', y='mark', data=avg_marks_gender)
plt.title('Average Marks by Gender')
plt.xlabel('Gender')
plt.ylabel('Average Marks')
plt.show()
```
<img width="981" height="638" alt="image" src="https://github.com/user-attachments/assets/a09172ea-a2f8-4c12-87b3-0bcaffe665c2" />

I grouped the data by gender and calculated the average student marks using the mean() function. I then created a bar chart with Seaborn to compare the average marks for each gender.
The bar chart clearly compared the average marks between male and female students, making it easy to identify any differences in their overall academic performance.

---


-
### Google Colab Notebooks

- **Python Project 1:**  
  [Python Project 1 Notebook](https://colab.research.google.com/drive/1IKe2b5X9UOWP72AW84ZMno2Uhq8a11Ek)

- **Python Visualisation:**  
  [Python Visualisation Notebook](https://colab.research.google.com/drive/12HdO4dzpy9JFQYoSTpl809MSiKgM7tk1)

These notebooks include the Python code, analysis, and visualisations completed as part of the Data Technician Skills Bootcamp.

---

# Skills Demonstrated

- Python programming
- Data analysis
- Data cleaning
- Exploratory data analysis (EDA)
- Data visualisation
- Pandas
- Matplotlib
- Seaborn
- Google Colab
- Interpreting data
#  Tools & Technologies
Python
Google Colab
Pandas
Matplotlib
Seaborn

