# Life Expectancy

**Introduction**

This project features a dashboard that visualizes the relationship between age and expected remaining months of life across varying mortality levels. By integrating life expectancy data and risk factors, it provides an interactive tool to explore how age and mortality influence longevity, making it valuable for industries like insurance, healthcare, and financial planning.

Life expectancy (LE) is determined through statistical and actuarial methods that analyze a combination of individual and population-level factors to estimate the average remaining lifespan. These LE reports assess key elements such as medical history, lifestyle choices, age, gender, family health history, as well as socioeconomic and behavioral factors.



**The Data**

For this dataset, I analyzed 800 life expectancy reports from an unnamed underwriter. The data focuses exclusively on non-smoking individuals, using a non-tobacco-referenced mortality table, with ages ranging from 60 to 100 years.

Key Life Expectancy Metrics:

- Certificate Age: The individual's age on the date the certificate was issued.
- Referenced Mortality Table: The baseline table used for calculations, with non-tobacco tables applied if tobacco use is undocumented.
- Mortality Multiplier: A factor applied to adjust baseline mortality rates based on health conditions, increasing or decreasing the estimated life expectancy.
- Mean Life Expectancy: The average remaining lifespan across the group.
- Median Life Expectancy: The age at which half of a hypothetical group of 1,000 similar individuals would have died.

The key data points used in this project include the certificate age, mean life expectancy, and mortality multiplier.

**The Results**

To determine the mortality rating of an individual, start by referencing standard mortality tables (e.g., 100) based on the individual's age and gender as a baseline. Then, evaluate the individual's unique risk factors, including any chronic health conditions, lifestyle choices (such as smoking or activity level), family medical history, and socioeconomic factors. If they have significant health risks or a history of chronic illnesses, their mortality rating may be higher (e.g., 150, 200 or more), indicating a shorter life expectancy. Conversely, if the individual is in good health with few risk factors, their rating may be lower (e.g., 100 or below), reflecting a longer life expectancy. 

You can explore the dashboard's interactive graph [here.](https://public.tableau.com/shared/D9JNJPZXX?:display_count=n&:origin=viz_share_link)

The graphs below show that as age increases, life expectancy decreases across all mortality multipliers, with higher mortality multipliers (e.g., 200) resulting in significantly shorter life expectancies compared to lower ones (e.g., 100).

Male
![](https://github.com/marvin-gomez/life_expectancy/blob/main/Data%20visuals/male_nonsmoker.png)

Calculations to determine the life expectectancy at different mortalitly ratings:

100% Motality:\
Mean = 0.00270589*(Age)^3 + -0.555676*(Age)^2 + 28.946*(Age) + -13.8695\
R-Squared: 0.975533\
P-value: < 0.0001

150% Motality:\
Mean = 0.00264464*(Age)^3 + -0.547247*(Age)^2 + 29.5462*(Age) + -106.55\
R-Squared: 0.982855\
P-value: < 0.0001

200% Motality:\
Mean = 0.00549051*(Age)^3 + -1.22965*(Age)^2 + 84.1551*(Age) + -1579.32\
R-Squared: 0.993527\
P-value: < 0.0001

Female

![](https://github.com/marvin-gomez/life_expectancy/blob/main/Data%20visuals/female_nonsmoker.png)

100% Motality:\
Mean = 0.000436905*(Age)^3 + 0.0202581*(Age)^2 + -19.9206*(Age) + 1391.08\
R-Squared: 0.977296\
P-value: < 0.0001

150% Motality:\
Mean = 0.00303064*(Age)^3 + -0.61233*(Age)^2 + 31.7275*(Age) + -45.0509\
R-Squared: 0.98782\
P-value: < 0.0001

200% Motality:\
Mean = 0.00195311*(Age)^3 + -0.335199*(Age)^2 + 8.79437*(Age) + 550.088\
R-Squared: 0.985183\
P-value: < 0.0001




This project highlights the critical role life expectancy data plays in understanding longevity and its applications across various industries. By visualizing the relationship between age, mortality rates, and remaining lifespan, this analysis provides valuable insights for informed decision-making in such places like:

- Life Insurance: Adjusts premiums and risk profiles.
- Life Settlements: Affects the valuation of life insurance policies.
- Healthcare: Guides treatment plans and resource allocation.



