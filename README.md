# DATA-ANALYSIS Climate Change and Its Impact on Natural Disasters

## Team Members
- Harish SELVAKUMAR
- Artemiy Smogunov
- Nissanth
- Vincent Ly
- Tristan Pichard
- Iness Bennai

## Table of Contents
1. [Introduction](#introduction)
2. [Descriptive Statistics of One and Two Variables](#descriptive-statistics)
3. [Correlation Between Climate Change and Natural Disasters](#correlation-climate-disasters)
4. [Correlation Analysis of Various Data Related to Climate Change](#correlation-analysis)
5. [Principal Component Analysis (PCA)](#pca)
6. [Conclusion](#conclusion)

---

## Introduction
Climate change is a major global concern, with its effects increasingly visible in the form of more frequent and severe natural disasters such as storms, floods, droughts, and wildfires. This project aims to analyze the impact of climate change on these disasters through data analysis techniques. By investigating recent trends, we seek to identify patterns and correlations that can help inform strategies for mitigating climate-related disasters.

## Descriptive Statistics of One and Two Variables
### Key Findings:
- The average number of natural disasters per year from 2011 to 2020 was approximately **326**, compared to **300 per year** from 2000 to 2010, indicating a **10% increase**.
- Using data from STATISTA, we compared the number of natural disasters in 2022 with the average from 2002 to 2021 and found that **2022 often exceeded the average**.
- This led us to investigate the potential correlation between climate change (temperature increases) and the rise in natural disasters.

## Correlation Between Climate Change and Natural Disasters
To assess the relationship between climate change and natural disasters:
- We analyzed a graph from *Alternative Économique* that shows trends in natural disasters alongside temperature changes in less developed countries.
- We calculated the **covariance** between the number of natural disasters and temperature variations to determine their statistical relationship.
- Using regression analysis:
  - Regression equation: **y = 0.0088x + 13.687**
  - The **least squares method** was used to establish the best-fit line for the data.

## Correlation Analysis of Various Data Related to Climate Change
We collected climate and natural disaster data for the years **2016–2020** from reliable sources.

### Methodology:
- Created a **data matrix** where each row represents a year and each column represents a parameter.
- Developed a **correlation matrix** using the standardized centered matrix method.
- Wrote a **MATLAB script** to automate correlation calculations.

### Key Observations:
- Temperature is strongly correlated with **rainy days, snowfall, and floods** but negatively correlated with **greenhouse gas emissions**.
- The number of hectares burned is slightly correlated with **agriculture and extreme weather days**.
- Rainy days and floods are negatively correlated with **greenhouse gas emissions**.
- Some inconsistencies, such as the impact of **COVID-19 in 2020**, were noted due to limited years in the dataset.

## Principal Component Analysis (PCA)
### Why PCA?
- Climate-related data comes in **different units and magnitudes**, requiring **data standardization** before analysis.
- We computed **eigenvalues** using MATLAB to identify the most significant components.
- Chose the **top three principal components** based on their explanatory power.

### Interpretation of Principal Components:
1. **Environmental Sustainability Axis**: Correlated with **rainfall, temperature, snow cover, and floods**; negatively correlated with **greenhouse gas emissions**.
2. **Vulnerability and Disaster Risk Axis**: Negatively correlated with **extreme weather, land burned, and car trips**.
3. **Transportation and Snow Cover Axis**: Correlated with **car trips and snowfall**, but negatively correlated with **burned land**.

### Geographical Representation:
- **Axis 1 represents France**.
- **Axis 2 represents Latvia**.
- **Axis 3 represents Norway, Sweden, and Iceland**.

## Conclusion
Our analysis confirms a **strong correlation between climate change and the frequency of natural disasters**. The data indicates that rising temperatures contribute significantly to extreme weather events such as storms, floods, droughts, and wildfires. These findings highlight the urgent need for global policies aimed at mitigating climate change and improving disaster resilience.

