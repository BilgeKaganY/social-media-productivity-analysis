Analyzing the Impact of Social Media Usage on Productivity
Project Description
This project aims to explore the relationship between personal social media usage—specifically YouTube and TikTok—and productivity levels, as measured by focused study time recorded in the Forest app. By analyzing my own data collected over a two-month period, I intend to gain insights into how consumption of social media platforms affects my ability to focus and maintain productivity in an academic setting. The ultimate goal is to identify patterns or correlations that could inform better time management strategies and improve overall focus.

Motivation
In today's digital age, social media has become an integral part of daily life, often consuming significant portions of our time and attention. As a student striving for academic excellence, I have observed that time spent on platforms like YouTube and TikTok can sometimes interfere with my study habits and productivity. Understanding how my social media usage impacts my ability to focus is crucial for developing effective strategies to balance leisure and work. This project not only serves as personal introspection but also contributes to the broader understanding of digital distractions and their effects on productivity.

Data Sources
1. YouTube Watch History
Data Collected: The dataset includes video titles, channel names, and timestamps indicating when each video was watched.
Data Enhancement: To enrich the analysis, I plan to utilize the YouTube Data API to fetch additional information for each video, such as:
Video Durations: The length of each video to calculate total watch time per day.
Video Categories: Content categories (e.g., Education, Entertainment, Music) to analyze the types of content consumed.
Engagement Metrics: Optional metrics like view counts or likes, if relevant.
2. TikTok Screen Time Data
Data Collected: Daily total screen time spent on the TikTok app, manually recorded from the app's built-in screen time management features.
Data Characteristics: Since TikTok does not provide detailed activity logs, the data will focus on total usage time per day.
3. Forest App Productivity Data
Data Collected: Detailed records of focused study time, including:
Total Focus Time per Day: The cumulative duration of all focus sessions each day.
Number of Focus Sessions: How many times the app was used to initiate a focus session.
Focus Categories: If available, the types of tasks or subjects studied during each session.
Data Format: The app provides a timeline of focus periods, which will be organized into a structured dataset.
Project Plan
1. Data Collection and Enhancement
Continuous Data Logging: Regularly collect data from all three sources to ensure a comprehensive dataset.
YouTube Data Enhancement:
API Integration: Use the YouTube Data API to retrieve video durations and categories for each video in my watch history.
Data Alignment: Ensure that the additional data aligns correctly with the original watch history entries.
2. Data Preprocessing
Data Cleaning:
Handle missing or inconsistent data entries.
Standardize date and time formats across all datasets.
Data Integration:
Merge the datasets based on dates to create a unified view of social media usage and productivity for each day.
Feature Engineering:
Calculate total YouTube watch time per day by summing video durations.
Aggregate social media usage metrics (e.g., total screen time, number of videos watched).
Create additional features if necessary, such as average focus session length.
3. Exploratory Data Analysis
Descriptive Statistics:
Compute mean, median, and standard deviation for social media usage and productivity metrics.
Data Visualization:
Time Series Plots: Visualize trends in social media usage and productivity over time.
Scatter Plots: Examine the relationship between social media usage and productivity levels.
Bar Charts: Analyze the distribution of video categories watched on YouTube.
Correlation Analysis:
Calculate correlation coefficients to quantify the relationships between variables.
Identify any significant positive or negative correlations.
4. Machine Learning Modeling
Regression Analysis:
Objective: Predict productivity levels (e.g., total focus time per day) based on social media usage metrics.
Models Used: Linear regression, multiple regression models incorporating various features.
Evaluation Metrics: R-squared, Mean Squared Error (MSE), Mean Absolute Error (MAE).
Classification:
Objective: Classify days into 'High Productivity' and 'Low Productivity' based on focus time.
Approach: Use classification algorithms such as Logistic Regression, Decision Trees, or Random Forest.
Evaluation Metrics: Accuracy, Precision, Recall, F1 Score.
Cross-Validation:
Implement cross-validation techniques to assess the robustness of the models.
5. Interpretation of Results
Statistical Findings:
Interpret the results from the EDA and machine learning models.
Discuss the strength and significance of any correlations found.
Hypothesis Evaluation:
Assess whether the data supports the initial hypothesis that increased social media usage negatively impacts productivity.
Insights and Patterns:
Identify any unexpected patterns or anomalies in the data.
Explore possible explanations for observed trends.
6. Documentation and Reporting
Methodology Documentation:
Record all steps taken during data collection, preprocessing, analysis, and modeling.
Include code snippets, algorithms used, and justification for methodological choices.
Comprehensive Report:
Prepare a detailed report summarizing the project, including:
Introduction and objectives
Methods and materials
Results and discussion
Conclusion and recommendations
Future Work:
Reflect on the limitations of the study, such as sample size or data quality.
Suggest areas for future research or improvements to the methodology.
Technologies and Tools
Programming Language: Python
Data Analysis Libraries: Pandas, NumPy
Data Visualization Libraries: Matplotlib, Seaborn
Machine Learning Libraries: Scikit-learn
APIs and Tools: YouTube Data API
Version Control: Git and GitHub
Integrated Development Environment (IDE): Jupyter Notebook, Visual Studio Code
