# Analyzing the Impact of Social Media Usage on Productivity

## Project Description
This project explores the relationship between personal social media usage and productivity levels, as measured by focused study time recorded in the Forest app. Since my primary social media platform is TikTok, I have collected data from this app. By analyzing my own data collected over a two-month period, I aim to gain insights into how TikTok usage affects focus and productivity in an academic setting. The ultimate goal is to identify patterns or correlations that could inform better time management strategies and improve overall focus.

## Motivation
In today's digital age, social media has become an integral part of daily life, often consuming significant portions of our time and attention. As a student working to boost my attention span, I have observed that time spent on TikTok can interfere with study habits and productivity. 

**Hypothesis**: Increased screen time on TikTok is negatively correlated with productivity, as measured by focus time in the Forest app. This project aims to test whether excessive screen time leads to reduced productivity.

Understanding how social media usage impacts focus is crucial for developing strategies to balance leisure and work.

## Data Sources

### TikTok Screen Time Data
- **Collected Data**: Daily total screen time, manually recorded from the app's built-in features.
- **Data Characteristics**: Includes total usage time, day/night screen time, and log counts.

### Forest App Productivity Data
- **Collected Data**:
  - Total focus time per day.
  - Number of focus sessions.
  - Focus categories.
- **Data Format**: Structured timeline of focus periods.

## Project Plan and Progress

### 1. Data Collection and Preprocessing
- **Tasks Performed**:
  - Data cleaning to handle missing or inconsistent entries.
  - Standardized date formats for consistency.
  - Merged TikTok and Forest app datasets based on dates for a unified analysis.

### 2. Feature Engineering
- **Features Created**:
  - Focus Efficiency: `TotalFocusTime / TotalLogCount`
  - Categorized high vs. low productivity days.

### 3. Exploratory Data Analysis (EDA)
- **Tasks Performed**:
  - Visualized time series trends for screen time and focus time.
  - Conducted correlation analysis between variables.
  - Examined weekly patterns of screen time and focus time using heatmaps.
  - Tested the hypothesis: "As screen time increases, focus time decreases."

### 4. Machine Learning Modeling
#### Regression Analysis
- **Objective**: Predict daily focus time (productivity) based on social media usage.
- **Model**: Multiple Linear Regression
- **Results**:
  - Provided insights into the predictability of focus time from screen time.
  - Evaluated using metrics like Mean Absolute Error (MAE) and R-squared.

#### Classification
- **Objective**: Classify days into 'High Productivity' and 'Low Productivity.'
- **Model**: Random Forest Classifier
- **Results**:
  - Classification performance evaluated using accuracy, precision, and recall.

### 5. Statistical Analysis
- **Objective**: Validate the hypothesis using statistical methods.
- **Tasks Performed**:
  - Pearson correlation analysis.
  - Hypothesis testing using statistical significance (p-values).

### 6. Findings
- **Correlation**: No strong correlation was observed between total screen time and focus time. While some patterns suggest a possible decrease in focus time with increased screen time, this relationship was not statistically significant.
- **Hypothesis Result**: Based on statistical tests, the hypothesis that "as screen time increases, focus time decreases" was **rejected** due to insufficient evidence of a strong negative correlation.
- **Productivity Insights**: Days with moderate screen time often showed better productivity compared to extremely high or low screen time days.
- **Machine Learning**: Regression models did not perform well due to the lack of strong predictors, but the classification model successfully identified high and low productivity days with reasonable accuracy.

### 7. Documentation and Reporting
- **Tasks Performed**:
  - Created comprehensive visualizations for insights.
  - Summarized results, limitations, and recommendations for better time management.

## Limitations and Future Work
### Limitations
- **Small Dataset**: The analysis was limited by the amount of data collected, which may not represent broader trends.
- **Focus on TikTok**: Other potential productivity-affecting factors, like other apps or non-digital distractions, were not included.

### Future Work
- **Expanded Data Collection**: Include data over a longer time period and consider incorporating other social media platforms for comparison.
- **Enhanced Modeling**: Experiment with more complex machine learning models for predicting focus time.
- **Behavioral Analysis**: Explore additional behavioral metrics, such as breaks taken or specific focus categories.

## Technologies and Tools
- **Programming Language**: Python
- **Data Analysis Libraries**: Pandas, NumPy
- **Data Visualization Libraries**: Matplotlib, Seaborn
- **Machine Learning Libraries**: Scikit-learn
- **Version Control**: Git and GitHub
- **IDE**: Jupyter Notebook, Visual Studio Code
