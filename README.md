**How Social Media Usage Affects Mental Health — Data Analysis**

**Project Overview:**

This project explores how daily social media usage impacts mental health indicators such as stress levels and sleep quality across different age groups, genders, and platforms.

Using Exploratory Data Analysis (EDA) with Python, this project uncovers patterns and insights from real survey data — answering 7 key research questions with meaningful visualizations.


**Dataset Description:**

FeatureDescriptionAgeRespondent age (16–49 years)GenderMale / Female / OtherDaily_Screen_Time(hrs)Hours spent on social media per daySleep_Quality(1-10)Self-reported sleep quality scoreStress_Level(1-10)Self-reported stress level scoreSocial_Media_PlatformPrimary platform used (Facebook, Instagram, TikTok, YouTube, LinkedIn, X)

Total Records: 500 respondents
Platforms Covered: Facebook, Instagram, TikTok, YouTube, LinkedIn, X (Twitter)
Age Range: 16 to 49 years


**Research Questions:**

1. Does higher daily screen time lead to higher stress levels?
2. Which social media platform has the most stressed users?
3. Does more screen time negatively affect sleep quality?
4. Which age group experiences the highest stress and most screen time?
5. Do stress levels differ across genders on different platforms?
6. Which platform's users report the worst sleep quality?
7. Who has the worst combined profile — highest stress + worst sleep + most screen time?


**Tools & Libraries Used:**

ToolPurposePython 3Core programming languagePandasData cleaning and manipulationMatplotlibBase visualizationsSeabornAdvanced statistical chartsNumPyNumerical operationsGoogle ColabDevelopment environment


**Visualizations Used:**

QuestionChart TypeScreen Time vs StressBar ChartPlatform vs StressHorizontal Bar ChartScreen Time vs SleepScatter Plot + HeatmapAge Group AnalysisLine Chart + Bar ChartGender × Platform StressGrouped Bar ChartPlatform vs Sleep QualityBar Chart + Box PlotWorst-Case ProfileHeatmap + Bar Chart


**Key Findings:**

* Instagram users report the highest average stress level (6.96/10) and worst sleep quality (5.91/10) among all platforms
* A negative correlation exists between daily screen time and sleep quality — more screen time leads to worse sleep
* High screen time users (6+ hrs) show significantly higher stress levels compared to low usage groups
* Young adults (16–25) tend to use social media the most and are among the most stressed age groups
* Stress levels vary notably across genders and platforms — certain combinations show particularly high-risk patterns
* A filtered group of users with stress ≥ 8, sleep quality ≤ 4, and screen time ≥ 6 hrs represents the highest-risk segment for digital wellness intervention


**How to Run This Project:**

* Option 1 — Google Colab (Recommended)

Open the .ipynb file in Google Colab
Upload the CSV dataset using the left panel file upload
Click Runtime → Run All
All charts will appear below each cell


* Option 2 — Local (Jupyter Notebook)

bashpip install pandas matplotlib seaborn numpy jupyter
jupyter notebook social_media_mental_health_analysis.ipynb


**Conclusion:**

This analysis shows a clear relationship between heavy social media usage and declining mental health indicators. Platforms like Instagram are associated with higher stress and poorer sleep, particularly among younger users. These findings suggest that digital wellness awareness and screen time management can meaningfully improve mental health outcomes.


**Author**

Yamuna S

Linkedin : www.linkedin.com/in/yamuna-s-615138361
