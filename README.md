# Nigeria-s-Disease-Burden-Development-Analysis-1990-2021-

<img width="1106" height="792" alt="Screenshot 2025-11-18 210804" src="https://github.com/user-attachments/assets/41e8c246-4da0-4420-84af-4aa04e2d69d9" />


PROJECT OVERVIEW

Between 1990 and 2021, Nigeria experienced major political, economic, and social transitions. This project explores how those shifts are reflected in the country’s health outcomes, particularly its DALYs (Disability-Adjusted Life Years),  one of the strongest measures of population health.

Using data from IHME (GBD) and the World Bank, I analyzed:

-Trends in total disease burden

-Correlations between DALYs and development indicators

-Regression models explaining what drives health improvements

This repository includes:

-Cleaned datasets

-Code for trend analysis, correlation analysis, and OLS regressions

-Visualizations

-Summary interpretations

-A ready-to-run Jupyter Notebook

KEY QUESTIONS

-Is Nigeria’s disease burden improving or worsening over time?

-How are development indicators changing within the same period?

-Do economic and social development indicators predict health improvements?

-What does Nigeria’s epidemiological transition actually look like?

METHODS 
1. Trend Analysis

-DALYs (total + cause-specific) from 1990–2021

-GDP per capita, life expectancy, HDI, urbanization

2. Correlation Analysis

-Examined how strongly each development indicator relates to DALYs.

3. Regression Modeling

Built several OLS models to quantify the strength of association between:

-DALYs (dependent variable)

-GDP per capita

-Life expectancy

-Urbanization

-HDI

SUMMARY OF FINDINGS
1. Total DALYs dropped from ~122,000 to ~55,000 per 100,000 (1990–2021)
Communicable DALYs declined by ~50%

Nigeria’s overall disease burden has improved over 30 years, although
progress is not linear.

2. Communicable diseases ↓ | NCDs ↑

Communicable DALYs declined by ~50%

NCD DALYs increased slightly from ~17,000 to ~16,000 but with fluctuations

The data shows a clear epidemiological transition.

3. Development indicators are improving

GDP per capita rose from ~$1,550 → ~$2,400, peaking above $2,600 in 2014

Life expectancy increased steadily from ~45 → ~55 years

Life expectancy, HDI, and urbanization all steadily increased.

4. Strong negative relationships with DALYs

<img width="1023" height="801" alt="Screenshot 2025-11-16 214318" src="https://github.com/user-attachments/assets/3d23ca98-5bd6-40bf-92d7-f5101350e663" />


GDP per capita ↘ DALYs (strong negative)

Life expectancy ↘ DALYs (very strong negative)

Urbanization ↘ DALYs (moderate negative)

Higher development → lower disease burden.

5. Regression models explain up to 99.8% of variation

Development is a powerful predictor of national health outcomes.

📂 DATA SOURCES 

-Global Burden of Disease (GBD) Data — IHME
https://ghdx.healthdata.org/gbd-results-tool

(Dataset: DALYs Total, Communicable, NCD, Injuries)

-World Development Indicators — World Bank

(Dataset: GDP per capita: https://data.worldbank.org/indicator/NY.GDP.PCAP.KD?locations=NG,

Life Expectancy:https://data.worldbank.org/indicator/SP.DYN.LE00.IN?locations=NG, 

Urbanization: https://data.worldbank.org/indicator/SP.URB.TOTL.IN.ZS?locations=NG)

-UNDP Human Development Index (HDI)
https://hdr.undp.org/data-center/documentation-and-downloads

NOTEBOOK

You can view or run the full analysis here:
👉 [GBD.ipynb](https://github.com/user-attachments/files/23644819/GBD.ipynb)

CONTACT

If you want to discuss the project, collaborate, or suggest improvements, feel free to reach out.

Ugoeze Unegbu

Public Health Data Analyst & Researcher

📧 zinalucy@gmail.com 

🔗 linkedin.com/in/ugoeze-lucy

⭐ If you find this useful, please star the repo!

It helps others discover the project.
