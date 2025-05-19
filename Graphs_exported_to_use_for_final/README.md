# DSA210-Term-Project: Diet, Exercise and Health Metrics

I am a student from Sabancı University, Toprak Aras and this is my DSA210 term project. 

---

## Hypothesis

**Diet and exercise significantly influence BMI, weight change, and energy levels.**

---

## Motivation

Understanding how daily habits such as nutrition, sleep, and exercise affect physical health is important for long-term well-being. This project uses real daily records to explore how inputs like calorie intake, workout intensity, and sleep quality relate to weight and energy levels.

---

## Project Goal

To analyze and model the impact of diet and physical activity on weight and energy levels using statistical methods and machine learning. Predictive models are built to estimate energy levels and weight changes from lifestyle inputs.

---

##  Data Sources and Preprocessing

The data was collected manually and exported from Apple Health and meal tracking logs. The file contains:
- **Daily records** of carbohydrates, proteins, calories, step count, sleep hours, sleep quality, workout intensity, energy levels, and weight.

**Preprocessing steps included:**
- Converting categorical columns (e.g., workout intensity) to numeric values
- Removing or imputing missing data
- Scaling numerical features using standardization

---

## Exploratory Data Analysis (EDA)

- Distribution analysis of key variables such as energy level and step count
- Correlation heatmaps between predictors and targets
- Boxplots and line charts to explore trends and outliers

---

## Hypothesis Testing

Various statistical tests were applied:
- **Pearson correlation** to measure strength between variables like `step count` and `energy level`
- P-values were used to determine statistical significance at α = 0.05

---

##  Visualizations

This section presents the key visual insights drawn from the project dataset.

---

### 1. Daily BMI Change Over Time
This line plot visualizes the day-to-day change in BMI based on weight records and a fixed height assumption. A red dashed line at zero helps identify whether the BMI increased or decreased on a given day.

![Bmi_Change_Time_Series](https://github.com/user-attachments/assets/13b7ba0c-0a83-45a3-8f9a-0acb7ef86d09)

---

### 2. Calories vs Energy Levels
This scatter plot shows the relationship between calorie intake and energy level ratings. The plot can indicate if higher calorie intake correlates with higher energy.

![Calories_vs_Energy_Levels](https://github.com/user-attachments/assets/1af381c7-d240-4e95-838d-7856f1238d59)

---

### 3. Daily Calorie Intake Trend
This line graph demonstrates daily caloric intake over time. It helps identify peaks, dips, and trends across days.

![Daily_Calorie_Intake_Graph](https://github.com/user-attachments/assets/ccf388ac-12af-4dee-a7dc-fcb2d5dc2983)

---

### 4. Carbohydrates vs Energy Levels
This scatter plot visualizes the relationship between carbohydrate intake (in grams) and energy levels. It helps assess if more carbs result in higher perceived energy.

![Carbonhydrates_vs_Energy_Levels_Graph](https://github.com/user-attachments/assets/2015dc7e-8ab4-42b1-9fd1-cefb169e91bd)

---

### 5. Correlation Heatmap
The heatmap shows pairwise correlation values between input features and outcomes such as energy level and weight. This helps detect which features are most associated with health metrics.

![Correlation_Heatmap](https://github.com/user-attachments/assets/18d545c7-7e30-426f-b18b-bbb100423089)

---

### 6. Energy Levels Distribution
This histogram illustrates how frequently each energy level (from 1 to 10) occurs in the dataset. It helps understand common patterns in perceived energy.

![Energy_Levels_Distribution_Graph](https://github.com/user-attachments/assets/7bd50ba6-ab0c-4e8c-a77a-b888084a0f82)

---

### 7. Step Count vs Energy Levels
This scatter plot explores the relationship between number of steps taken and energy levels, providing insight into how physical activity affects perceived energy.

![Step_Count_vs_Energy_Levels_Graph](https://github.com/user-attachments/assets/1cf92445-98f3-46df-844e-7bbd8e345ef6)
