# Life Expectancy

**Introduction**

This project features a dashboard that visualizes the relationship between age and expected remaining months of life across varying mortality levels. By integrating life expectancy data and risk factors, it provides an interactive tool to explore how age and mortality influence longevity, making it valuable for industries like insurance, healthcare, and financial planning.

Life expectancy (LE) is determined through statistical and actuarial methods that analyze a combination of individual and population-level factors to estimate the average remaining lifespan. These LE reports assess key elements such as medical history, lifestyle choices, age, gender, family health history, as well as socioeconomic and behavioral factors.

You can explore the dashboard's interactive graph [here.](https://public.tableau.com/shared/D9JNJPZXX?:display_count=n&:origin=viz_share_link)

**The Data**

The data was collected from 800 Life expectancy reports from an unnammed underwriter.  

Key Life Expectancy Metrics:

Certificate Age: The individual's age on the date the certificate was issued.\
Referenced Mortality Table: The baseline table used for calculations, with non-tobacco tables applied if tobacco use is undocumented.\
Mortality Multiplier: A factor applied to adjust baseline mortality rates based on health conditions, increasing or decreasing the estimated life expectancy.\
Mean Life Expectancy: The average remaining lifespan across the group.\
Median Life Expectancy: The age at which half of a hypothetical group of 1,000 similar individuals would have died.

The key data points used in this project include the certificate age, mean life expectancy, and mortality multiplier.

More about the mortality multiplier: 

Mortality multipliers adjust baseline mortality rates from standard tables to reflect an individual's unique risk profile. A multiplier above 1.0 indicates higher mortality risk, shortening life expectancy, while a multiplier below 1.0 suggests lower risk, extending it.





For this i used soley non-smoking individuals 
individuals age range observeers is between 60 to 100

**The Results**

Here are the calculations 

Mean = 0.146652*Certificate_Age^2 + -30.5796*Certificate_Age + 1615.44


Life expectancies can be applied: 

Life Insurance: Adjusts premiums and risk profiles.\
Life Settlements: Affects the valuation of life insurance policies.\
Healthcare: Guides treatment plans and resource allocation.\



