# Railway Data Analysis and Journey Duration Prediction Using Machine Learning

## 📌 Overview
This project was developed as part of my Data Science internship at Sysslan IT Solutions. It focuses on analyzing Indian railway operational data and developing machine learning models to predict train journey duration.
The project follows a structured data science workflow, including data exploration, data cleaning, exploratory data analysis (EDA), visualization, feature engineering, model development, and evaluation.

## 🎯 Objectives
- Explore and understand railway operational data.
- Clean and preprocess inconsistent or invalid records.
- Analyze station traffic, train routes, journey duration, and distance patterns.
- Visualize trends and relationships in the dataset.
- Build a regression model to predict journey duration.
- Evaluate model performance using MAE and RMSE.

## 📊 Project Tasks
### Task 1: Data Exploration
Examined dataset structure, columns, descriptive statistics, train routes, station information, and data quality.

### Task 2: Data Cleaning and Preprocessing
Handled duplicate records, parsed arrival and departure times, and derived journey duration, total distance, and number of stops.

### Task 3: Exploratory Data Analysis
Analyzed station traffic, identified busy and less-busy stations, and examined the relationship between distance and journey duration.

### Task 4: Data Visualization
Created histograms, bar charts, distribution plots, and scatter plots to communicate patterns in the railway data.

### Task 5: Journey Duration Prediction
Developed a Linear Regression model using total distance and number of stops as input features to predict journey duration in hours.

### Task 6: Segment-Level Prediction
Developed an additional Linear Regression model using distance to estimate journey duration for individual train segments.

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab / Jupyter Notebook

## 🔍 Key Findings
- Total journey distance showed a positive relationship with journey duration.
- Train traffic was unevenly distributed across stations, with major hubs handling more trains.
- Journey duration had a right-skewed distribution, with a smaller number of long-haul journeys.
- Data preprocessing was important for handling inconsistent time formats, duplicate records, and invalid duration values.

## 🤖 Model and Evaluation
Algorithm: Linear Regression
Primary model features: Total Distance and Number of Stops
Target variable: Journey Duration (Hours)
Train-test split: 80% training and 20% testing
Evaluation metrics: Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE)


## 📁 Project Structure
The project implementation was organized into six Jupyter Notebook tasks. The repository structure and notebook filenames will reflect the source files uploaded to this repository.

## 🚀 Future Improvements
- Explore advanced regression models such as Random Forest and Gradient Boosting.
- Investigate additional features that may improve prediction accuracy.
- Explore train delay prediction using suitable historical data.
- Integrate real-time railway data where an appropriate data source is available.
- Develop an interactive dashboard for railway data exploration.

## 👩‍💻 Internship Details
Organization: Sysslan IT Solutions  
Internship Domain: Data Science  
Project: Railway Data Analysis and Journey Duration Prediction Using Machine Learning

This project was completed as part of a Data Science internship and demonstrates practical experience in data preprocessing, exploratory analysis, visualization, and supervised machine learning.
