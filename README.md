# Gender and Age Group Variations in Suicide Rates Across Different Countries
## Contents
Research Question
Data Preparation
Exploratory Data Analysis
Data Storytelling
Research Question
The research question explored in this project is: “How do suicide rates vary by gender and age groups across different countries?”
Suicide remains a leading cause of death globally. By identifying high-risk groups, we can allocate resources effectively, making this a critical public health priority. Insights from this analysis can guide policymakers in crafting targeted interventions to prevent suicides, especially in specific age groups and cultural contexts.

## Data Source: Kaggle Dataset

### Data Preparation
#### Steps Taken:
##### Handling Age Groups:
The original dataset had age groups in ranges (e.g., "14-34"). To tidy the dataset, I split these into two separate columns and calculated the mean age for each range, rounding it to the nearest whole number for analysis.

##### Data Type Conversion:
The column gdp_for_year was of object data type. It was converted to integer type for proper mathematical analysis and to avoid errors in calculations.

##### Removing Zero Values:
Rows with zero suicide counts in the suicide_no column were removed. These rows do not contribute to the analysis of suicide patterns and could distort the results.

##### Handling Missing Values:
Missing values were identified and handled to maintain data integrity, ensuring reliable analysis.

##### Identifying and Removing Outliers:
Outliers in several variables were identified and removed to prevent skewed analysis. However, some extreme but genuine outliers remained as they represent real, impactful values.

## Exploratory Data Analysis
### Univariate Analysis:
#### Distribution of Suicide by Gender (Pie Chart):
The pie chart shows the distribution of suicides by gender, identifying imbalances in suicide rates between males and females.

#### Distribution of Suicides by Age Group (Histogram):
The histogram illustrates the frequency of suicides across different age groups, with a positive skew indicating that individuals in the 30-40 age range have higher suicide rates.

### Multivariate Analysis:
#### Suicides by Gender and Age Groups (Boxplot):
The boxplot compares suicide rates across genders and age groups, revealing that males have a higher suicide rate, with a steeper increase in middle-aged males.

#### Suicides by Gender and Country (Stacked Bar Chart):
The stacked bar chart visualizes the distribution of suicides by gender across different countries, highlighting cultural and societal differences.

#### Suicides by Age Group and Country (Heatmap):
The heatmap reveals the geographical variations in suicide rates by age group, with darker colors indicating higher suicide rates in specific countries and age groups.

### Bivariate Analysis:
##### Relationship Between GDP per Capita and Population (Scatter Plot):
The scatter plot analyzes the relationship between GDP per capita and population, showing that countries with higher GDP tend to have larger populations.

## Data Storytelling
Suicide remains a pressing global issue. Through data storytelling, we explore patterns of suicide across genders, age groups, and countries to design effective intervention strategies.

#### Gender-Based Imbalances:
Males consistently show higher suicide rates, with middle-aged males being particularly vulnerable. This indicates the need for targeted mental health interventions for this group.

#### Geographical Distribution:
Regions like Latin America and Eastern Europe show higher suicide rates, suggesting cultural, economic, and social factors at play.

#### Time Trends:
Both genders exhibit fluctuations in suicide rates over the years, highlighting the importance of ongoing monitoring and timely interventions.

#### Economic Influence:
While wealth (GDP per capita) does not correlate directly with suicide rates, it underlines that mental well-being is influenced by various factors beyond economic stability.

#### Age Group Insights:
Middle-aged individuals are most at risk, suggesting that stressors specific to this life stage need further investigation.

#### Dashboard:
A dashboard was created to visualize key insights, including trends over time, gender-based distributions, and geographical hotspots for suicide rates.

# Conclusion
This analysis highlights the urgency of addressing suicide, especially within vulnerable demographic groups. Gender, age, and geographical factors all play a role in shaping suicide rates. Understanding these variations is key to creating effective, targeted suicide prevention strategies.

