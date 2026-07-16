# Python Projects

## Student Marks Data Analysis and Visualisation

# What I Did

During this project I:

- Imported the dataset into Google Colab.
- Loaded the data into a Pandas DataFrame.
- Explored the dataset to understand its structure.
- Checked the data for missing values.
- Generated descriptive statistics.
- Created multiple visualisations using Matplotlib and Seaborn.
- Compared student marks across different classes.
- Analysed marks by gender.
- Interpreted the results of each visualisation.

---

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


Each visualisation helps answer a different question about the dataset and demonstrates my ability to present data in a clear and meaningful way.

---

# Key Findings

1 Most students achieved marks between approximately 70 and 90, showing generally good overall performance.

**What this means Teachers can quickly identify the overall performance level of students and recognise whether results are concentrated within a particular range.

---
 2 Student performance varies across different classes, with some classes achieving higher average marks than others.

**What this means  Schools can investigate differences between classes to understand factors affecting student achievement and provide additional support where required.

---
3 The visualisations also compare average marks by gender, making it easier to identify similarities and differences in student performance.

*What this means Educational organisations can use this information to monitor equality of outcomes and ensure all students receive appropriate support.

---

# Evidence

The following files demonstrate the work completed during this project:

- Python_project_1.ipynb
- https://colab.research.google.com/drive/1IKe2b5X9UOWP72AW84ZMno2Uhq8a11Ek#scrollTo=5yfvPk1I-g2M
- Python_Visualization.ipynb
- https://colab.research.google.com/drive/12HdO4dzpy9JFQYoSTpl809MSiKgM7tk1#scrollTo=zjJ6icySFcQr

These notebooks include the Python code, analysis and visualisations produced during the Bootcamp.

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

