Mental Health & Global Wealth: A Multi-Level Data Analysis
📌 Project Overview
This project investigates the relationship between economic development and mental health. By utilizing a "Macro-to-Micro" approach, I analyze global prevalence rates across nations (2019) alongside individual behavioral survey data (290,000+ responses) to uncover the hidden drivers of mental well-being.

📂 Data Sources
Global_Mental_Health_vs_GDP_2019.csv: Country-level statistics on GDP and prevalence of 5 major mental disorders.

Mental_Health_Behavioral_Survey.csv: Individual-level data regarding workplace stress, treatment history, and lifestyle habits.

📊 Key Dashboards & Insights
The following visualizations (located in the /outputs folder) tell the story of my findings:

1. Global Prevalence Ranking
Insight: Identifies the top 10 countries by total mental health burden. It highlights that high-income nations often report the highest cumulative prevalence rates.

2. Wealth vs Depression Paradox
Insight: A regression analysis showing the positive correlation between GDP and Depression. This "Wealth Paradox" suggests that economic growth does not automatically lead to better mental health outcomes.

3. Gender Treatment Gap
Insight: Explores the social barriers to mental health care. The data reveals significant differences in treatment-seeking behavior between genders.

4. Indoor Time vs Mood Stability
Insight: A behavioral deep-dive showing how physical isolation (time spent indoors) directly impacts the frequency and severity of mood swings.

5. Disorder Correlation Matrix
Insight: A statistical heatmap demonstrating the high comorbidity between Anxiety and Depression, providing a clinical view of how these disorders overlap globally.

🛠️ Technical Implementation
This project was developed using Python in a Google Colab environment.

Data Cleaning: Handled missing values and standardized Timestamp columns into Date formats.

EDA: Utilized Pandas for aggregation and Seaborn for advanced statistical visualization.

Correlation Analysis: Performed Pearson correlation to understand the links between economic wealth and health metrics.
