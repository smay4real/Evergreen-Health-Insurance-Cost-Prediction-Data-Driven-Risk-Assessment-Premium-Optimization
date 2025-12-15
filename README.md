# Evergreen-Health-Insurance-Cost-Prediction-Data-Driven-Risk-Assessment-Premium-Optimization


![1_QAXeG8YoPuFucU_D3S4dpg](https://github.com/user-attachments/assets/85a74f52-ef41-479f-a84a-70b3a7049208)


Introduction

In the healthcare industry, understanding the factors that drive insurance costs is critical for both insurance companies and policyholders. Medical insurance premiums are not arbitrary, they are carefully calculated based on a complex interplay of demographic, lifestyle, and health-related factors that predict healthcare utilization and costs.

This portfolio project presents a comprehensive analysis of health insurance charges using a real-world dataset of 1,338 insured individuals. The analysis explores how variables such as age, BMI (Body Mass Index), smoking status, number of dependents, gender, and geographic region influence insurance premiums. Through statistical analysis, pattern recognition, and predictive insights, this project demonstrates the power of data analytics in actuarial science and healthcare economics.


The Data Story

The Setting

This dataset represents a snapshot of health insurance customers across four major U.S. regions; Southeast, Southwest, Northwest, and Northeast.

Each record captures a moment in time: an individual’s health profile and the corresponding annual insurance charges they face.


The Characters

Demographics:

1,338 insured individuals spanning ages 18 to 64

Perfect gender balance: 50.5% male, 49.5% female

Four geographic regions with roughly equal representation

Diverse family structures: 42.9% have no children, while 57.1% are supporting dependents


Health Profiles:

Average BMI of 30.66 (classified as “obese” by WHO standards)

20.5% smokers vs. 79.5% non-smokers

BMI distribution: Only 18.4% in “normal” or “underweight” categories

52.7% classified as obese or severely obese


Financial Picture:

Total insurance revenue: $17.76 million annually

Average annual charge: $13,270.42 per person

Massive range: From $1,121.87 (lowest) to $63,770.43 (highest)

High variation: 91.3% coefficient of variation indicates extreme charge dispersion


The Plot Twist

The data reveals a startling truth: smoking status is the single most powerful predictor of insurance costs, dwarfing all other factors. Smokers pay an average of $32,050 annually, 3.8 times more than non-smokers ($8,434). This $23,616 premium represents the actuarial reality of smoking-related healthcare costs.

But the story doesn’t end there. The interaction between smoking and obesity creates a multiplicative effect:

Non-smoking, normal-weight individuals: ~$7,735 average

Smoking + severely obese individuals: ~$43,556 average (5.6x higher!)

This is a tale of compound risk — where lifestyle factors don’t just add up, they multiply.



Objective of the Project

Primary Objectives

1. Identify Key Cost Drivers

Goal: Determine which factors (age, BMI, smoking, children, sex, region) have the strongest statistical relationship with insurance charges

Method: Correlation analysis, regression modeling, comparative statistics

Deliverable: Ranked list of cost drivers with quantified impact

Business Value: Informs premium pricing formulas and risk assessment models


2. Quantify Premium Differentials

Goal: Calculate the exact dollar impact of each risk factor on insurance charges


Example Questions:

How much more do smokers pay than non-smokers?

What is the cost increase per BMI point?

How do charges increase with age?

Deliverable: Pricing multipliers and differential tables

Business Value: Enables transparent, data-backed rate cards


3. Detect Interaction Effects

Goal: Identify how combinations of factors multiply risk (e.g., smoking + high BMI)

Method: Interaction term analysis, segmentation by multiple variables

Deliverable: Risk profiles for customer archetypes

Business Value: Reveals compound risk scenarios requiring specialized pricing


4. Profile High-Cost Customers

Goal: Characterize the demographic and health attributes of the top 25% most expensive customers

Method: Quartile analysis, comparative profiling

Deliverable: High-risk customer persona documentation

Business Value: Targeted interventions, risk mitigation strategies, fraud detection



What Does Success Mean to the Company?

They demonstrate how your insurance products: whether health, life, or property, helping clients navigate difficult situations, recover financially, or gain peace of mind. building trust and credibility.



DATA SPLIT:

1.Category One — Independent Values

Age

Smokers

Region

Children

Sex


2. Category Two — Dependent Values

BMI (Body Mass Index)

charges


POTENTIAL ANALYSIS / QUESTIONS

1. How does age affect BMI and charges

2. Is there a correlation between smoking habits and BMI/charges?

3. Are there regional differences in BMI and charges?

4 Do certain regions have higher or lower BMI and charges compared to others?

5 How does the presence of children affect BMI and charges?

6. Are there differences in BMI and charges between individuals with and without children?

7. Are there significant differences in BMI and charges between males and females?

8. How do independent variables such as age, smokers, region, children, and sex affect charges?

9. How does BMI vary across different age groups and regions?

10. Are there significant differences in BMI and charges between smokers and non-smokers?



POTENTIAL INSIGHTS

1. Smokers tend to have higher charges compared to non-smokers, potentially due to increased health risks.

2. Certain regions have higher average BMI and charges, indicating potential differences in healthcare access, lifestyle, or socioeconomic factors.

3. Older age groups tend to have higher BMI and charges, possibly due to increased health risks and healthcare utilization.

4. Sex differences in BMI and charges: Males or females may have different average BMI and charges, potentially due to differences in lifestyle, health behaviors, or healthcare-seeking patterns.

5. Presence of children affects charges: Individuals with children may have higher charges due to increased healthcare utilization for their dependents.

6. BMI is a significant predictor of charges: Higher BMI is associated with increased charges, potentially due to the costs of treating obesity-related health conditions.



ANALYSIS:


CHARGES BY AGE GROUP: Column chart

![1_IVxlw91XWb3WCABg7Kd4Eg](https://github.com/user-attachments/assets/c4d1e64d-59b0-4979-a79b-3b6e79390c80)


Observations:

1. The age group 43–47 has the highest total charges at $2.3M+, topping all other age brackets.

2. Age groups 58–62, 48–52, and 53–57 follow closely, each exceeding $2.2M in total charges.

3. Young adults aged 18–22 rank fifth, with charges over $1.8M — higher than several older groups.

4. The 63–67 age group has the lowest total charges, under $1M.

5. Charges fluctuate across age groups, showing no consistent upward or downward trend with age.

Pre-Insights:

1. The spike in charges for ages 43–47 may reflect increased health risks or policy utilization during midlife, suggesting a need for targeted wellness or cost-containment strategies.

2. High charges in late 50s and early 60s support the assumption of elevated healthcare costs with age, but the midlife peak challenges a purely age-based pricing model.

3. Elevated charges among 18–22-year-olds could point to accident-prone behavior, maternity claims, or early chronic conditions warranting deeper analysis of claim types.

4. The drop in charges for seniors (63–67) might be due to fewer policyholders, reduced coverage, or transition to public healthcare indicating a potential gap in senior engagement.

5. Since age alone doesn’t predict charges reliably, integrating other variables like smoker status, BMI, and region could improve risk modeling and premium accuracy.


2. SMOKERS VS NON-SMOKER: Pie Chart

![1_Gk4oo_HL7-fHUQHbINQiXw](https://github.com/user-attachments/assets/61cafff9-a984-4d0a-961d-eb35a98696aa)

Observations:

1. Smokers dominate the population, accounting for 79.49% of the dataset.

2. Non-smokers make up only 20.51%, indicating a significant imbalance.

3. The chart shows a binary classification with no intermediate categories (e.g., former smokers).

4. The visual contrast between segments is stark, with smokers occupying nearly four-fifths of the pie.

5. This distribution suggests that smoking is a common lifestyle trait among the insured individuals.

Pre-Insights:

1. The high proportion of smokers may correlate with elevated health risks and higher insurance charges, warranting targeted health interventions.

2. This imbalance could skew the company’s risk pool, potentially increasing overall claims and affecting premium pricing.

3. Marketing and wellness programs could be tailored to smoking cessation, offering incentives for healthier behavior.

4. The data may reflect regional or demographic trends cross-referencing with age, region, and BMI could uncover deeper patterns.

5. The company might consider policy adjustments or differentiated premiums to manage the financial impact of smoking-related claims.



3. Amount Charges Per Regions — Bar Chart

![1_puYv9caUflF3OKZTOoMrtA](https://github.com/user-attachments/assets/179a327f-bec0-4d5c-8695-4ac971c5c28a)


Observations

1. Southeast region leads with the highest total charges at $5.36M, significantly ahead of other regions.

2. Northeast follows with $4.34M, showing strong utilization but still trailing the Southeast.

3. Northwest and Southwest are nearly tied, both hovering around $4.01M–$4.03M.

4. The gap between Southeast and Southwest exceeds $1.35M, indicating notable regional disparity.

5. All four regions show substantial charge volumes, suggesting a wide geographic spread of insured individuals.

Pre-Insights:

1. The Southeast’s dominance in charges may reflect higher population density, more smokers, or elevated BMI average warranting targeted cost-control strategies.

2. Regional differences in charges could be influenced by local healthcare costs, lifestyle factors, or policy uptake rates.

3. The near parity between Northwest and Southwest suggests similar risk profiles or demographic compositions — potentially useful for regional benchmarking.

4. The Northeast’s strong performance might be linked to older age groups or higher average claims, which could inform regional underwriting adjustments.

5. A deeper dive into region-wise smoker ratios, BMI, and age distribution could help explain the cost variations and guide product localization.



4. BMI By Region — Line Chart

![1_GtEl8M53epa3UNBALiOo8A](https://github.com/user-attachments/assets/5091c13e-3209-4269-9d29-993ade79939c)

Observations

1. Southeast region has the highest BMI at 27.20%, noticeably above the others.

2. Southwest and Northwest are tied at 24.29%, indicating similar health profiles.

3. Northeast has the lowest BMI at 24.22%, though only slightly below the others.

4. The BMI variation across regions is modest, with a spread of less than 3 percentage points.

5. The chart suggests a regional clustering of BMI values, with Southeast standing out as an outlier.

Pre-Insights

1. The elevated BMI in the Southeast may signal higher lifestyle-related health risks, potentially driving up insurance claims and charges.

2. Similar BMI levels in Southwest and Northwest suggest comparable health behaviors or demographics, useful for regional policy standardization.

3. Northeast’s slightly lower BMI could reflect better health awareness, access to care, or demographic differences.

4. The narrow BMI range across regions implies that BMI alone may not explain regional cost disparities — other factors like moking or age might be more influential.

5. Targeted wellness campaigns in the Southeast could help reduce BMI-related risks, improving both health outcomes and cost efficiency.


5. CHILDREN COUNT PER CHARGES - Line Chart

![1_ogYrmKB8Ayeg6Awq_UfbRg](https://github.com/user-attachments/assets/2fb5e9c3-416e-4715-948e-e18c1a3c27a7)

Observations:

1. Charges increase steadily from 0 to 3 children, peaking at $15,355.32 for families with 3 children.

2. Families with 2 children also show high charges, at $15,073.56, nearly matching the peak.

3. Charges drop for families with 4 children, falling to $13,850.66.

4. Families with 5 children show the lowest charges, at $8,786.04, a sharp decline from the peak.

5. The trend is non-linear, with a rise up to 3 children followed by a decline, suggesting other influencing factors.

Pre-Insights

1. The peak at 3 children may reflect higher healthcare utilization, possibly due to increased family coverage or pediatric needs.

2. The drop at 5 children could indicate lower coverage levels, cost-conscious behavior, or policy limitations for larger families.

3. Families with 2–3 children may represent a high-value segment for targeted products or bundled coverage plans.

4. The non-linear trend suggests that number of children alone doesn’t predict charges — cross-analysis with income, region, or smoker status could clarify.

5. Insurance offerings could be optimized by tiering benefits based on family size, ensuring affordability and coverage balance.



6. AVERAGE CHARGES BY SMOKER’S STATUS — Donut chart

![1_kLZ-B4Kfgz0gnLZZfXSkkA](https://github.com/user-attachments/assets/d760424a-6993-4b09-a458-eef227660daf)


Observations:

1. Smokers incur an average charge of $32,050.23, while non-smokers average $8,434.27 a nearly 4x difference.

2. The donut chart visually emphasizes this disparity, with smokers occupying a larger segment due to their higher costs.

3. Smokers likely require more frequent or intensive healthcare services, possibly due to chronic conditions linked to smoking.

4. Non-smokers show significantly lower medical expenses, suggesting fewer or less severe health interventions.

The contrast between the two groups highlights a clear cost divide, making lifestyle choices a visible factor in healthcare economics.

Pre-Insights:

1. Smoking is strongly correlated with higher healthcare utilization and chronic illness, driving up costs.

2. The financial burden of smoking supports the case for higher insurance premiums, risk-based pricing, and targeted health policies.

3. Non-smokers can serve as a benchmark for healthy behavior, reinforcing the value of reward-based insurance models and preventive care incentives.

4. Public health campaigns and policy makers can use this data to quantify the economic impact of smoking and promote cessation programs.

5. Employers and insurers may leverage these insights to design wellness initiatives, subsidies, or incentive structures that encourage smoke-free lifestyles.

POST-ANALYSIS OBSERVATION

1. High Regional Charges in Southeast
The Southeast region incurs the highest total charges and has the highest average BMI, suggesting a strong link between regional health metrics and insurance costs.

2. Smokers Drive Disproportionate Costs
Smokers represent only 21.5% of customers but contribute nearly 40% of total charges, with an average charge nearly six times higher than non-smokers.

3. BMI Trends by Region
BMI levels vary significantly by region, with Southeast at 32.1 and Northeast at 28.3, indicating regional lifestyle or health disparities.

4. Flat Charges Across Age Groups
All age groups show identical charges, which is atypical and may indicate data normalization or a flat-rate pricing model.

5. Children Count Correlates with Lower Charges
Customers with more children tend to have lower charges, especially those with five children, who show the lowest cost.

6. Gender Distribution Not Explicitly Highlighted
While gender is color-coded, there’s no direct analysis of gender-based trends in charges or health metrics.

7. Northwest Region Shows Balanced Metrics
The Northwest has moderate charges and BMI, suggesting a more balanced customer profile.

8. Non-Smokers Dominate Customer Base
Despite lower average charges, non-smokers make up the majority of the customer base, contributing to overall cost stability.

9. Average BMI Above Healthy Range
The overall average BMI of 30.15 is in the obese category, indicating a potential health risk across the customer base.

10. Total Customers Presented as a Decimal
The customer count is shown as 13,270.42, which may be a data formatting issue or an artifact of averaging.

STRATEGIC RECOMMENDATION

1. Launch Regional Wellness Campaigns
Target high-BMI regions like the Southeast with fitness and nutrition programs to reduce long-term health costs.

2. Introduce Smoker Cessation Incentives
Offer premium discounts or rewards for smokers who enroll in cessation programs to lower their risk profile.

3. Segment Pricing by Age Group
Reevaluate the flat-rate model and introduce age-based pricing to reflect actual risk and usage patterns.

4. Promote Family Plans for Larger Households
Encourage bundled coverage for families with multiple children, as they tend to generate lower charges.

5. Enhance Gender-Based Analytics
Include gender-specific insights to uncover potential disparities in health outcomes or cost drivers.

6. Optimize Coverage in High-Cost Regions
Review policy structures in the Southeast to ensure pricing reflects the elevated health risks and costs.

7. Educate Customers on BMI and Health Risks
Provide personalized health reports and BMI tracking tools to raise awareness and encourage healthier lifestyles.

8. Refine Data Presentation Standards
Correct anomalies like decimal customer counts to improve clarity and professionalism in reporting.

9. Leverage Predictive Modeling
Use machine learning to forecast future costs based on smoker status, BMI, region, and family size.

10. Monitor and Adjust Non-Smoker Benefits
Consider enhancing benefits for non-smokers to reward healthier behavior and retain low-risk customers.

CONCLUSIONS
Overall Performance Assessment:
Evergreen Insurance Company demonstrates a moderate-to-high risk portfolio with significant opportunities for optimization. The 20.51% smoker ratio and 25% average BMI indicate substantial health risk exposure that directly impacts profitability.

Critical Success Factors:
Strengths:

Large customer base (13,270+ customers) provides economies of scale
Clear data insights enabling targeted interventions
Diverse age distribution spreads risk across cohorts
Family customer segment shows favorable risk profile
Vulnerabilities:

High smoker concentration creating cost pressure
Geographic risk concentration in Southeast
BMI levels approaching overweight classification
Peak claims in critical middle-age segment
Priority Action Plan (Next 12 Months):
Immediate (0–3 months):

Launch smoking cessation pilot program in Southeast
Implement BMI-based wellness incentives
Review and adjust smoker premium differential
Short-term (3–6 months):

Roll out regional health initiatives in Southeast
Expand marketing in northwest/southwest regions
Deploy preventive care programs for 43–62 age group
Medium-term (6–12 months):

Measure impact of wellness programs on claims
Refine risk-based pricing models
Develop family-focused product enhancements
Expected Outcomes:
Claims reduction: 10–15% reduction in smoking-related claims
Customer acquisition: 20% increase in low-risk segment
BMI improvement: 5% reduction in overweight/obese customers
Profitability: 8–12% improvement in combined ratio
FINAL RECOMMENDATION
Evergreen Insurance should adopt a dual-strategy approach: aggressively manage existing high-risk populations through wellness interventions while simultaneously expanding market share in lower-risk geographic and demographic segments. The data clearly indicates that smoking status and regional health factors are the primary cost drivers, making these the focal points for immediate action.

Success Metric: Reduce smoker ratio from 20.51% to below 18% and improve Southeast region BMI from 27.20% to below 26% within 18 months, targeting a $2–3M annual cost savings.














