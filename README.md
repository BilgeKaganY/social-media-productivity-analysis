# Analyzing the Impact of Social Media Usage on Productivity

## Project Description
This project explores the relationship between personal social media usage and productivity levels, as measured by focused study time recorded in the Forest app. Since my primary social media platforms are Youtube and Tiktok, I have collected data from these apps. By analyzing my own data collected over a two-month period, I aim to gain insights into how consumption of social media platforms affects focus and productivity in an academic setting. The ultimate goal is to identify patterns or correlations that could inform better time management strategies and improve overall focus.

## Motivation
In today's digital age, social media has become an integral part of daily life, often consuming significant portions of our time and attention. As a student working to boost my attention span, I have observed that time spent on platforms like YouTube and TikTok can interfere with study habits and productivity. Understanding how social media usage impacts focus is crucial for developing strategies to balance leisure and work. 

## Data Sources

### YouTube Watch History Data
- **Collected Data**: Video titles, channel names, and timestamps. Collected via google takeouts in html format.
- **Data Enhancement**:
  - **Video Durations**: Calculate total watch time per day.
  - **Video Categories**: Analyze types of content consumed (Education, Entertainment, Music).
  - **Engagement Metrics**: Optionally include metrics like view counts or likes.

### TikTok Screen Time Data
- **Collected Data**: Daily total screen time, manually recorded from the app's built-in features.
- **Data Characteristics**: Focused on total usage time per day.

### Forest App Productivity Data
- **Collected Data**:
  - Total focus time per day.
  - Number of focus sessions.
  - Focus categories.
- **Data Format**: Structured timeline of focus periods.

## Project Plan

### 1. Data Collection and Enhancement
- **Continuous Data Logging**: Regularly collect data from all sources.
- **YouTube Data Enhancement**:
  - API Integration: Use the YouTube Data API to retrieve additional information.
  - Data Alignment: Ensure additional data aligns with original entries.

### 2. Data Preprocessing
- **Data Cleaning**: Handle missing or inconsistent entries.
- **Standardization**: Standardize date and time formats.
- **Data Integration**: Merge datasets based on dates for a unified view.

### 3. Feature Engineering
- Calculate total YouTube watch time per day.
- Aggregate social media usage metrics (total screen time, number of videos watched).
- Create additional features, such as average focus session length.

### 4. Exploratory Data Analysis (EDA)
- **Descriptive Statistics**: Compute mean, median, and standard deviation.
- **Data Visualization**:
  - Time series plots to visualize trends.
  - Scatter plots to examine relationships between variables.
  - Bar charts for YouTube video categories.
- **Correlation Analysis**: Quantify relationships between variables.

### 5. Machine Learning Modeling
#### Regression Analysis
- **Objective**: Predict productivity levels (total focus time per day).
- **Models Used**: Linear regression, multiple regression.
- **Evaluation Metrics**: R-squared, Mean Squared Error (MSE), Mean Absolute Error (MAE).

#### Classification
- **Objective**: Classify days into 'High Productivity' and 'Low Productivity'.
- **Approach**: Use Logistic Regression, Decision Trees, or Random Forest.
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1 Score.
- **Cross-Validation**: Assess robustness of models.

### 6. Interpretation of Results
- **Statistical Findings**: Strength and significance of correlations.
- **Hypothesis Evaluation**: Assess impact of social media usage on productivity.
- **Insights and Patterns**: Identify trends or anomalies and their possible explanations.

### 7. Documentation and Reporting
- **Methodology Documentation**: Record all steps, code snippets, and justifications.
- **Comprehensive Report**:
  - Introduction and Objectives
  - Methods and Materials
  - Results and Discussion
  - Conclusion and Recommendations

## Technologies and Tools
- **Programming Language**: Python
- **Data Analysis Libraries**: Pandas, NumPy
- **Data Visualization Libraries**: Matplotlib, Seaborn
- **Machine Learning Libraries**: Scikit-learn
- **APIs and Tools**: YouTube Data API
- **Version Control**: Git and GitHub
- **IDE**: Jupyter Notebook, Visual Studio Code
