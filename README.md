# Nike_Sales_2024_Analysis

## Project Background

Nike is a global sportswear brand founded in 1964. They sell a wide variety of athletic apparel and accessories, but are most recognized for their shoes. They have offerings for at every price level, including budget, mid-range, and premium items. 
The company has just released their 2024 data on sales, product offerings, and price tiers. I have been approached by Nike's Sales and Marketing teams to thoroughly analyzes and synthesizes this data to uncover critical insights that will improve Nike’s online premium product sales to meet a goal of 70% Percentage of Revenue Online (PRO).

## Insights and recommendations are provided on the following key areas:
•	**Monthly Sales**: An evaluation of premium sales revenue and volume by month. 

•	**Regional Comparisons**: An assessment of premium online sales performance by region.

•	**Online Product Offering Performance**: An analysis of premium products online sales percentages and Percentage of Revenue Online (PRO). 

The SQL queries used to inspect and clean the data for this analysis can be found [here](https://github.com/nbellinder/Nike_Sales_2024_Analysis/blob/main/Data%20Exploration).

Targeted SQL queries regarding various business questions can be found [here](https://github.com/nbellinder/Nike_Sales_2024_Analysis/blob/main/Sales%20Analysis).

An interactive Tableau dashboard used to report and explore sales trends can be found [here](https://public.tableau.com/app/profile/nolan.bellinder/viz/Nike2024PremiumProductSalesAnalysis/SalesDataDash?publish=yes).

## Data Structure & Initial Checks

The companies sales database structure as seen below consists of one table: nike_sales_2024 with a total row count of 1000 records. 
Executive Summary
## 
Overview of Findings

Online premium product sales are worst in April, with only 64.7% of revenue coming from online sales and 69% of product lines failing to meet our 70% PRO goal. Our weakest overall sub category for premium online sales is Football with only a 64% PRO and 54% of product lines failing to meet our 70% PRO goal. The following sections will explore additional insights and highlight key opportunity areas for improvement with individual product lines.

Below is the overview page from the Tableau dashboard and more examples are included throughout the report. The entire interactive dashboard can be downloaded [here](https://public.tableau.com/app/profile/nolan.bellinder/viz/Nike2024PremiumProductSalesAnalysis/SalesDataDash?publish=yes).

![image](https://github.com/user-attachments/assets/b5bc6701-ddab-49c1-890f-9a1b4af3b8a8)

## Insights Deep Dive
### Monthly Sales:

•	Despite having the worst monthly PRO in 2024, April had the second highest Average Online Purchase Price for all of 2024 at $190. This can be attributed to a spike in online sales of accessory Bags carrying an Average Online Purchase Price of $244 for April. The yearly PRO on Bags was 54% in 2024 but jumped to 62% in April. It was also our greatest revenue driver in April brining in $26.7 million in online sales for the month, nearly double our second most popular product line for the month.

•	A large factor in poor online sales for April 2024 lies, predictably, in Rain Jackets. The PRO of Rain Jackets fell from a yearly average of 83% to 69% in April. With April being a typically rainy month,  it is hard to bear the convenience of purchasing a Rain Jacket in person when the need arises.

•	Overall, April was a tough month for online sales as Rain Jackets, Mercurial, Compression Wear, Accessory Bags, and Hats all fell short of our 70% PRO goal. Additionally, Backpacks, Therma-Fit tops, Vapor Cricket, Air Jordan, Tech Fleese tops, and Windrunners all failed to eclipse 60% PRO and represent significant areas for improvement.

•	While April was our worst month by PRO, August, September, October, and November all fell short of our 70% PRO goal as well. This shows a glaring seasonal weakness that can be addressed as PRO drops from 73.2% in July to 66.5% in August and only weakly crosses our PRO goal to 70.3% by December. 

![image](https://github.com/user-attachments/assets/2d9b5ea4-c078-4e0f-8bf4-b66f2c15bf9b)


### Regional Comparisons:

•	India, Japan, and Southeast Asia all areas of strength for online sales metrics. All three regions have a PRO over 70% and are our three best regions by Average Online Purchase Price with $194, $193, and $184 respectivley which is at least $15 more than the next highest region. Japan is also our second strongest market for Total Online Revenue un excess of $188 million in 2024. However, India and Southeast Asia are our second and third worst performing regions by Total Online Revenue at $146 million and $155 million. Aditionally, India had the lowest Total Units Sold Online with only 752,873 units.

•	Of 7 total regions, only 3 are below out 70% PRO goal, South Korea, Greater China, and America. South Korea has the strongest PRO of the group at 69.6%, barely missing our goal. South Korea is our second best region by Total Units Sold Online with 1,039,464. However, with an Average Online Purchase Price of just $160, our lowest by any region, they generate only the third hightst Total Online Revenue at nearly $167 million. This is just about $4 million more than America in 4th place and over $20 million behind second place Japan.

•	China provided incredibly strong Total Online Revenue at $209 million despite a 68% PRO. Interestingly, China has a Percentage of Units Sold Online of 68.9% which indicates a nearly 1% gap in online Unit Sales and online Revenue which would make sense given it has the second lowest Average Online Purchase Price at $161.

•	Our strongest overall region is Japan. Japan has a PRO of 71.6% despite having a Percentage of Units Sold Online of 71%. This can be attributed to their $193 Average Online Purchase Price, just $1 behind the leader India. Howver, their volume is far greater as Japan is the third best performing region in Total Units Sold Online at 971,982 and second in Total Online Revenue at $188 million. To quikcly compare Japan to South Korea, as they are both second and third in Total Online Revenue and Total Online Units Sold: Japan's sales trailed South Korea's by around 70,000 units however Japan's Total Online Revenue exceeded that of South Korea by nearly $20 million with only a 2% difference in PRO.

![image](https://github.com/user-attachments/assets/bbfaa858-68da-4127-9d5e-278c845de24b)


### Category 3:

•	Main insight 1. More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.

•	Main insight 2. More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.

•	Main insight 3. More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.

•	Main insight 4. More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.

[Visualization specific to category 3]

### Category 4:

•	Main insight 1. More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.

•	Main insight 2. More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.

•	Main insight 3. More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.

•	Main insight 4. More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.

[Visualization specific to category 4]

## Recommendations:

Based on the insights and findings above, we would recommend the [stakeholder team] to consider the following:

•	Specific observation that is related to a recommended action. Recommendation or general guidance based on this observation.

•	Specific observation that is related to a recommended action. Recommendation or general guidance based on this observation.

•	Specific observation that is related to a recommended action. Recommendation or general guidance based on this observation.

•	Specific observation that is related to a recommended action. Recommendation or general guidance based on this observation.

•	Specific observation that is related to a recommended action. Recommendation or general guidance based on this observation.

## Assumptions and Caveats:

Throughout the analysis, multiple assumptions were made to manage challenges with the data. These assumptions and caveats are noted below:

•	Assumption 1 (ex: missing country records were for customers based in the US, and were re-coded to be US citizens)

•	Assumption 1 (ex: data for December 2021 was missing - this was imputed using a combination of historical trends and December 2020 data)

•	Assumption 1 (ex: because 3% of the refund date column contained non-sensical dates, these were excluded from the analysis)
