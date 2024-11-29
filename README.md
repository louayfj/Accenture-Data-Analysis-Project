# SocialBuzz Data Analysis Project

![Top Categories and Sentiment Analysis](https://github.com/louayfj/Accenture-Data-Analysis-Project/blob/main/Accenture%20Project/Visualization/Top%20Categories%20and%20Sentiment%20Analysis.png?raw=true)


## Overview

The SocialBuzz Data Analysis Project is part of the **Accenture Virtual Internship Program for Data Analysts**. This project simulates a real-world scenario where data analysts work with a fast-growing social media platform to analyze content performance, optimize engagement strategies, and prepare for a successful IPO.

SocialBuzz is a rapidly growing platform with over 500M monthly active users and 100,000+ daily posts. The analysis provides actionable insights to improve content strategy and big data practices, showcasing the critical role of data analysts in strategic decision-making.

---

## Objectives

- Identify the **top 5 performing content categories** based on aggregate reaction scores.
- Perform **sentiment analysis** (positive, neutral, negative) to evaluate user engagement.
- Audit and enhance **big data practices** for scalability and efficiency.
- Deliver insights to aid in **IPO planning**.

---

## Tools Used

The following tools were utilized to ensure efficient analysis and visualization:

- **Python (Jupyter Notebook)**: For data cleaning, preparation, and analysis.
- **SQL**: To extract and merge data from various datasets.
- **Tableau**: For creating interactive visualizations, including bar charts, pie charts, and line charts.
- **Excel**: For final result consolidation and sharing insights.

---

## Project Process

1. **Data Extraction**  
   - Extracted and merged datasets from:
     - `Content.csv`
     - `Reactions.csv`
     - `ReactionTypes.csv`
   - Linked data using `Content ID` and `Reaction Type` as keys.

2. **Data Cleaning and Preparation**  
   - Addressed missing values and inconsistencies.
   - Prepared a clean dataset for analysis using Python.

3. **Data Analysis**  
   - Calculated aggregate popularity scores for content categories using Python and SQL.
   - Performed sentiment analysis on reaction types.

4. **Visualization**  
   - Created bar charts, pie charts, and line charts in Tableau to present insights.
   - Visualized trends in engagement, sentiment, and category performance.

5. **Documentation and Recommendations**  
   - Documented the entire process and delivered actionable insights to SocialBuzz.

---

## Key Insights

- **Top Categories**:  
  - **Animals** (11,958), **Food** (6,568), and **Healthy Eating** (6,105) lead in engagement scores.
- **Sentiment Analysis**:  
  - 83.83% of reactions were **positive**, 10.12% were **neutral**, and 6.05% were **negative**.
- **Engagement Trends**:  
  - Engagement peaked in **May 2021**, highlighting opportunities for replicating success.

---

## Next Steps

1. **Content Strategy**:  
   - Prioritize content in top-performing categories.
   - Address underperforming categories like **Science** and **Technology** to expand user interest.
   - Reduce negative sentiment through improved content strategies.

2. **Engagement Optimization**:  
   - Analyze the engagement peak of **May 2021** to identify success factors.
   - Develop a data-driven content calendar for high-impact campaigns.

3. **Big Data Enhancements**:  
   - Implement scalable systems for managing unstructured data.
   - Align practices with IPO readiness to ensure sustainable growth.

---

## Repository Structure

| File Name                             | Description                                                                                  |
|---------------------------------------|----------------------------------------------------------------------------------------------|
| `Content.csv`                         | Contains raw data on uploaded content and associated categories.                            |
| `Reactions.csv`                       | Details reactions on content, including reaction types.                                     |
| `ReactionTypes.csv`                   | Metadata for reaction types, including sentiment and popularity scores.                     |
| `Final_Output.xlsx`                   | Consolidated analysis results, including top categories and sentiment breakdown.            |
| `cleaned_dataset.ipynb`               | Jupyter notebook detailing data cleaning, merging, and analysis steps.                     |
| `Top Categories and Sentiment Analysis.twb` | Tableau workbook with interactive visualizations of key insights.                          |

---

## How to Use

1. **Run the Analysis**:  
   - Open `cleaned_dataset.ipynb` in Jupyter Notebook to follow the cleaning and analysis process.

2. **View the Visualizations**:  
   - Open `Top Categories and Sentiment Analysis.twb` in Tableau for interactive insights.

3. **Review the Results**:  
   - Use `Final_Output.xlsx` for a summary of the key findings and recommendations.

---

## About the Internship

This project is part of the **Accenture Virtual Internship Program** for aspiring data analysts. The program provides participants with hands-on experience in real-world data analysis scenarios, equipping them with practical skills and industry-relevant insights.

---

## Team Members

- **Mae Mulligan** - Project Lead (Managing Director, Accenture)  
- **Andrew Fleming** - Chief Technology Architect  
- **Marcus Rompton** - Senior Principal  

---

## Questions?

For inquiries or further details about this project, feel free to reach out!
