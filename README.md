# Student-Dataset_Python
# 📊 Python Data Analysis & Visualization Projects

This repository showcases a series of beginner-friendly Python projects focused on:
- Data cleaning and manipulation using **Pandas**
- Interactive data visualization with **Plotly Express**
- Applied problem-solving with real-life scenarios
- Enhancing user interaction via formatted inputs/outputs

---

## 📁 Dataset Overview

The dataset used (`student.csv`) contains anonymized student performance data, including:

| Column | Description                                     |
|--------|-------------------------------------------------|
| `id`   | Unique identifier for each student              |
| `name` | Student name (anonymized)                       |
| `class` | Educational level (e.g., "Four", "Five", etc.) |
| `mark` | Final mark out of 100                           |
| `gender` | Gender (may include missing values)           |

A sample of the data:

| id  | name     | class | mark | gender |
| --- | -------- | ----- | ---- | ------ |
| 1   | John Deo | Four  | 75   | female |
| 2   | Max Ruin | Three | 85   | male   |
| ... | ...      | ...   | ...  | ...    |

---

## 🔍 Exploratory Data Analysis (EDA)

Using `pandas`, we explored patterns and trends in student performance, including:

### ➤ Gender-Based Insights

- **Average Marks**:
  - Female students: `77.31`
  - Male students: `71.59`

- **Top Performers by Gender**:
  - Male: `88`
  - Female: `96`

### ➤ Class-Based Insights

- **Average Mark in Class Five**: `80.0`
- **Average for Males in Class Six**: `54.0`

### ➤ Student Name Filtering

- Extracted all students with `"John"` in their name using string-matching:
  ```python
  df.loc[df["name"].str.contains("John", case=False, na=False)]

### ➤ Sorting and Grouping

- Sorted students by **mark** and **name**  
- Grouped by **gender** and **class**, applying conditions for deeper insights
# Interactive Visualizations with Plotly Express

## 📊 Visualizations (Interactive - Plotly Express)

We created several interactive visualizations using `plotly.express`:

### ➤ Sorting and Grouping

- Sorted students by **mark** and **name**  
- Grouped by **gender** and **class**, applying conditions for deeper insights

### ➤ 🌐 Polar Line Plot of Student Marks
Visualizing student marks around a polar coordinate system.

https://github.com/user-attachments/assets/975c1001-6c03-46ac-9a19-aaae53ffb0bf

🧠 Python Exercises: Logic & Arithmetic

✔️ Exercise Highlights
These scripts demonstrate essential algorithmic thinking and user interaction in Python.

Task	Description
Visitor Greeting	Inputs name and age, prints a personalized message
Area Calculator	Inputs kitchen dimensions, computes area and cost
Temperature Converter	Celsius → Fahrenheit using formula
Distance Converter	Miles ↔ Kilometers conversions
Lucky Number	Sums digits of a 3-digit number
Secret Code	Reverses a 4-digit number to unlock clue
All exercises use standard input/output and Python fundamentals like //, %, string formatting, and conditional logic.

🧪 Sample Code Snippet

# Reverse a 4-digit number
num = int(input("Enter a 4-digit number: "))
a = num // 1000
b = (num % 1000) // 100
c = (num % 100) // 10
d = num % 10
print("Secret Code:", str(d) + str(c) + str(b) + str(a))

### 🚀 Skills Demonstrated

✅ Data wrangling with pandas
✅ Conditional filtering & boolean logic
✅ Data visualization with Plotly
✅ User interaction & formatted I/O
✅ Exploratory analysis & insights reporting
✅ Basic algorithm design (math & logic exercises)

### 💡 Future Improvements
- Add error handling for user inputs
- Expand dataset with more features (e.g., attendance, subject breakdowns)
- Build dashboard with Plotly Dash or Streamlit
- Automate report generation using Jupyter and nbconvert
