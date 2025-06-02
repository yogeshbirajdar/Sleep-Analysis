# Sleep-Analysis
"Effect of Sleep On Lifestyle" dashboard analyzes sleep patterns' impact on health. Visualizes sleep duration, disorders (Apnea, Insomnia), and stress levels correlating with heart rate, steps, &amp; BMI across occupations. Features an interactive gender filter for deep, gender-specific insights into well-being.

# Effect of Sleep On Lifestyle Dashboard

This repository contains the analysis and visualization of the "Effect of Sleep On Lifestyle," presented through an interactive dashboard. This dashboard provides a comprehensive view of how sleep-related factors intersect with various lifestyle metrics, including occupation, Body Mass Index (BMI), heart rate, and stress levels.

The dashboard utilizes a dark theme with yellow accents for Key Performance Indicators (KPIs) and titles, and various shades of grey for the charts and data fields, ensuring a clean and readable presentation.

## Dashboard Overview

The dashboard is structured to provide quick insights through top-level KPIs and detailed analyses via multiple chart types.

### 1. Top-Level KPIs and Filters

* *Avg. Heart Rate:* Displays the average heart rate across the dataset (e.g., *71*).
* *Avg. Daily Steps:* Shows the average daily steps taken (e.g., *7K*).
* *Avg. Physical Acti.:* Represents an average physical activity score or duration (e.g., *59*).
* *Gender Slicers (Top Right):* Features "Female" and "Male" slicers. These are interactive filters that, when selected, dynamically update *all charts* on the dashboard to display data specific to the chosen gender, enabling gender-specific analysis. (Note: In the provided image, neither is actively selected, indicating a view of the combined dataset).

### 2. Detailed Charts and Data Fields

The dashboard is organized into two primary rows of charts.

#### Row 1: Occupation and Sleep Disorder Related Metrics

* *Average Stress Level by Occupation (Bar Chart)*
    * *Purpose:* Compares average stress levels across different occupations.
    * *Insights:* Sales Representatives exhibit the highest average stress (8.00), followed by Salespersons (7.00). Lawyers show the lowest average stress (5.04).
    * *Data Fields:* Average Stress Level (Y-axis), Occupation (X-axis).

* *Average of Heart Rate by Sleep Disorder (Bar Chart)*
    * *Purpose:* Visualizes the average heart rate in relation to different sleep disorders.
    * *Insights:* Individuals with Sleep Apnea have significantly higher average heart rates (77.27) compared to those with Insomnia (73.24) or no sleep disorder (69.90), indicating a strong correlation.
    * *Data Fields:* Average Heart Rate (Y-axis), Sleep Disorder Type (X-axis).

* *Average Sleep Duration with Occupation (Bar Chart)*
    * *Purpose:* Shows the average sleep duration in hours for various occupations.
    * *Insights:* Lawyers tend to have the longest average sleep duration (7.4 hours), while Sales Representatives have the shortest (5.9 hours), suggesting a link between occupational stress and sleep duration.
    * *Data Fields:* Average Sleep Duration (Y-axis), Occupation (X-axis).

#### Row 2: BMI and Sleep Disorder Distribution

* *Count of Person ID by BMI Category (Treemap/Heatmap with numbers)*
    * *Purpose:* Visualizes the distribution of individuals across different BMI categories, with the size of the rectangle indicating the number of people.
    * *Insights:* The majority of the dataset's individuals fall into the "Normal" BMI category (131), followed by "Overweight" (42), "Obese" (9), and "Normal Weight" (7).
    * *Data Fields:* Count of Person ID, BMI Category.

* *Sleep Disorders by BMI (Bar Chart)*
    * *Purpose:* Displays the count of individuals categorized by their BMI.
    * *Insights:* This chart primarily reiterates the total distribution of individuals across BMI categories (Normal: 131, Overweight: 42, Obese: 9, Normal Weight: 7). While labeled for sleep disorders by BMI, it currently shows the total count of people within each BMI category.
    * *Data Fields:* Count of Individuals (Y-axis), BMI Category (X-axis).

* *Distribution of sleep disorders (Donut Chart)*
    * *Purpose:* Illustrates the proportion of the population affected by different sleep disorders.
    * *Insights:* A significant majority (137 individuals) report no sleep disorder. Among those with sleep disorders, Sleep Apnea (41 individuals) is more prevalent than Insomnia (11 individuals).
    * *Data Fields:* Count of Individuals by Sleep Disorder Type.

## Key Findings (Overall)

* *Overall Health Metrics:* The dataset indicates an average heart rate of 71, average daily steps of 7,000, and an average physical activity score of 59.
* *Occupation's Impact:* A strong correlation exists between higher occupational stress (e.g., Sales Representatives) and shorter average sleep durations.
* *Sleep Disorders and Heart Rate:* Individuals diagnosed with Sleep Apnea consistently show higher average heart rates, highlighting a potential cardiovascular risk.
* *BMI Distribution:* The majority of individuals in the dataset are categorized as "Normal" BMI.
* *Prevalence of Sleep Disorders:* Most individuals report no sleep disorders, with Sleep Apnea being more common than Insomnia among those affected.

## Interrelationships and Potential Insights

* The dashboard reveals a clear inverse relationship between average occupational stress and average sleep duration.
* It strongly suggests that sleep disorders, particularly Sleep Apnea, are associated with elevated heart rates.
* The interactive gender slicers are instrumental for deeper analysis, allowing users to explore how these trends and distributions vary between male and female populations.

## Dashboard Utility

This dashboard serves as a powerful analytical tool for understanding the complex interplay between sleep health and various lifestyle factors. It can be valuable for:

* *Healthcare Professionals:* To identify patient groups at risk due to sleep-related issues.
* *Researchers:* For further exploration into the correlations between sleep, lifestyle, and health outcomes.
* *HR Departments:* To develop targeted wellness programs to improve employee sleep health and overall well-being.
```
