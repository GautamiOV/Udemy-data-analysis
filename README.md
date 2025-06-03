# Udemy-data-analysis
# 📊 Udemy Courses Data Analysis Project

This project explores a dataset of Udemy courses to derive insights on course pricing, popularity, subject distribution, and more. It demonstrates skills in data analysis, visualization, and interpretation using **Python**, **Pandas**, **Matplotlib**, and **Seaborn**.

---

## 🎯 Project Objective

- Analyze Udemy course data to understand pricing strategies, course popularity, and subject trends.
- Perform Exploratory Data Analysis (EDA) to find meaningful patterns.
- Visualize key insights using effective plots and graphs.

---

## 🗃️ Dataset Description

- **Source**: Udemy Courses Dataset
- **Format**: CSV
- **Features**:
  - `course_id`: Unique identifier
  - `course_title`: Name of the course
  - `url`: Course URL
  - `is_paid`: Indicates if the course is free or paid
  - `price`: Price of the course
  - `num_subscribers`: Number of students enrolled
  - `num_reviews`: Number of reviews
  - `num_lectures`: Number of lectures in the course
  - `level`: Beginner, Intermediate, etc.
  - `content_duration`: Total duration in hours
  - `published_timestamp`: Date of publication
  - `subject`: Course category

---

## 🛠️ Tools & Technologies Used

- **Python**
- **Jupyter Notebook**
- **Pandas** – data manipulation
- **NumPy** – numerical operations
- **Matplotlib & Seaborn** – data visualization

---

## 🧪 Exploratory Data Analysis (EDA)

### ✅ Data Cleaning
- Checked for missing values and handled them appropriately
- Converted date columns to datetime format
- Removed unnecessary columns (like URL)

### ✅ Univariate Analysis
- Most common subjects (e.g., Business Finance, Web Development)
- Price distribution of courses
- Number of subscribers by subject
- Free vs. Paid course ratio

### ✅ Bivariate Analysis
- Relationship between price and number of subscribers
- Reviews vs. subscribers
- Course duration vs. number of lectures

### ✅ Correlation Matrix
- Visualized correlation between numerical features using a heatmap

---

## 📈 Key Visualizations

- Bar plot: Number of courses per subject
- Histogram: Course price distribution
- Bar plot: Total subscribers per subject
- Scatter plot: Reviews vs. subscribers
- Heatmap: Feature correlations

---

## 🔍 Key Insights

- **Web Development** and **Business Finance** are the most popular categories.
- Most courses are priced under $100, with several offered for free.
- Paid courses tend to attract more subscribers, especially in technical fields.
- There is a positive correlation between number of reviews and number of subscribers.

---

## 🙋‍♀️ About Me

I am a **Data Analyst** skilled in Python, SQL, Excel, and visualization tools. This project is part of my portfolio to showcase practical data analysis and storytelling capabilities.

📫 Email: ovgautami258@gmail.com
🔗 LinkedIn: [Your LinkedIn](https://www.linkedin.com/in/gautami-odithur-90b7ba287/)  

---

## 📌 How to Run the Project

### Requirements
- Python 3.8+
- Jupyter Notebook
- pandas, numpy, matplotlib, seaborn

### Steps
```bash
git clone https://github.com/yourusername/udemy-data-analysis.git
cd udemy-data-analysis
jupyter notebook
