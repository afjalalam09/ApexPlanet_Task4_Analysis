# 📊 Task 4: Data Storytelling & Statistical Validation

This repository contains my Task-4 (Final) submission for the ApexPlanet Data Analytics Internship.

## 🎯 Objective
To translate technical data findings into a compelling business narrative, statistically validate assumptions, and deliver actionable recommendations to stakeholders.

## 📖 The Data Story: From Problem to Strategy

### 1. The Business Assumption (The Setup)
It is a common business assumption that "Corporate" clients generate significantly higher average revenue per transaction compared to everyday "Consumer" clients.

### 2. Statistical Validation (The Conflict)
To avoid making decisions based on intuition, I ran an Independent T-Test (Two-tailed) using Python (`scipy.stats`) to validate this assumption[cite: 2].
*   **Null Hypothesis (H0):** There is no difference in average sales between the Consumer and Corporate segments[cite: 2].
*   **Alternative Hypothesis (H1):** There is a significant difference in average sales[cite: 2].

**The Results:**
*   **T-Statistic:** -0.5896[cite: 2]
*   **P-Value:** 0.5555[cite: 2]
*   **Conclusion:** Since the P-Value (> 0.05) is greater than the significance level, we **Fail to Reject the Null Hypothesis**[cite: 2].
*   **Meaning:** The data proves that there is NO significant difference in spending behavior between Consumer and Corporate segments[cite: 2].

### 3. Business Recommendation (The Resolution)
Since the spending behavior is statistically identical, I recommend adopting a **Unified Marketing Strategy** for both segments[cite: 1, 2]. The business should stop spending extra budget on separate "Corporate-only" outreach campaigns, as it does not yield higher returns per order, thereby saving marketing costs.

## 📁 Files Included
*   `cleaned_data.csv` - The core dataset used for final analysis.
*   `Task4_Hypothesis_Testing.ipynb` - Python notebook containing the T-Test and statistical validation[cite: 2].
*   `Task4_Final_Presentation.pptx` - The final Data Storytelling slide deck outlining the problem, findings, and strategy[cite: 1].

## 💻 Tools Used
*   **Python (SciPy, Pandas):** For statistical testing[cite: 2].
*   **PowerPoint:** For crafting the final business narrative[cite: 1].

## 🎥 Final Presentation Video
*   **LinkedIn Video Link:** [Watch my Final Presentation Here](https://www.linkedin.com/posts/afjalalam_dataanalytics-businessanalytics-statistics-activity-7419585839883739136-dJSe?utm_source=share&utm_medium=member_desktop&rcm=ACoAAETWFS0Bo2i86Or-ktk6m9YHn7elAPcHfCA)
*(Note: This video serves as my final presentation, where I narrate the data story and present my strategic recommendations to management).*
