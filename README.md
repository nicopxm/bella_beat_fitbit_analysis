# Bella Beat FitBit Analysis
Participants fitbit data usage is analyzed to find trends using jupyter notebook

# Introduction
Bellabeat, founded by Urška Sršen and Sando Mur, manufactures health-focused smart products tailored for women. Sršen's artistic background informs the design of technology aimed at empowering women with insights into their health and habits through data on activity, sleep, stress, and reproductive health. Since its inception in 2013, Bellabeat has rapidly grown into a prominent tech-driven wellness company. Sršen seeks to leverage consumer data analysis to identify growth opportunities, tasking the marketing analytics team with analyzing smart device usage data to inform strategic marketing decisions.

# Scenario 
As a junior data analyst at Bellabeat, you've been tasked with analyzing smart device fitness data to uncover growth opportunities. Urška Sršen, the company's Chief Creative Officer, believes that this analysis could help propel Bellabeat into a larger player in the global smart device market. Your focus will be on analyzing consumer usage patterns of one of Bellabeat's products to inform future marketing strategies. Your findings and recommendations will be presented to the executive team for consideration in the company's marketing strategy.
# Ask
1. What are some trends in smart device usage?
2. How could these trends apply to Bellabeat customers?
3. How can these trends help influence Bellabeat marketing strategy?

Primary stakeholders: Urška Sršen and Sando Mur, executive team members.
Secondary stakeholders: Bellabeat marketing analytics team.

# Business Task 
Identify smart device usage trends that can be applied to a Bellabeat product and serve as a growth and marketing opportunity for the company.

# Prepare
We're handling CSV dataset, essential and reliable, from kaggle but lacking comprehensive metadata. Governed by the CC0: Public Domain license, data access is restricted to authorized users with transparent privacy measures and regular security evaluations. Data integrity is ensured through various validation methods, though the absence of demographic details may introduce biases. The dataset comprises responses from a survey via Amazon, collected between 03.12.2016 and 05.12.2016, involving thirty-three Fitbit users consenting to share minute-level personal tracker data on physical activity, heart rate, and sleep. Reports are sortable by export session ID or timestamp, reflecting variations due to different Fitbit tracker models and user behaviors.

I will import the data set from Kaggle into Jupyter Lab where I can clean, filter, and analyze the data.

# Process 

# Import libraries
```import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import datetime as dt
import plotly.express as px
```


# Import datasets
```activity = pd.read_csv('/Users/Work/Documents/BellaBeat_case_study/fitbit_datasets/dailyActivity_merged.csv')
steps = pd.read_csv('/Users/Work/Documents/BellaBeat_case_study/fitbit_datasets/dailySteps_merged.csv')
hourly_steps = pd.read_csv('/Users/Work/Documents/BellaBeat_case_study/fitbit_datasets/hourlySteps_merged.csv')
hourly_calories = pd.read_csv('/Users/Work/Documents/BellaBeat_case_study/fitbit_datasets/hourlyCalories_merged.csv')
hourly_intensities = pd.read_csv('/Users/Work/Documents/BellaBeat_case_study/fitbit_datasets/hourlyIntensities_merged.csv')
```






