# Nike 2024 Premium Product Online Sales Analysis

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

The company's sales database structure as seen below consists of one table: nike_sales_2024 with a total row count of 1000 records. 

![image](https://github.com/user-attachments/assets/b57c065e-4733-44b8-a0b1-56af59ca98bf)

## Executive Summary
Overview of Findings

Online premium product sales are worst in April, with only 64.7% of revenue coming from online sales and 69% of product lines failing to meet our 70% PRO goal. Our weakest overall sub category for premium online sales is Football with only a 64% PRO and 54% of product lines failing to meet our 70% PRO goal. The following sections will explore additional insights and highlight key opportunity areas for improvement with individual product lines.

Below is the overview page from the Tableau dashboard and more examples are included throughout the report. The entire interactive dashboard can be downloaded [here](https://public.tableau.com/app/profile/nolan.bellinder/viz/Nike2024PremiumProductSalesAnalysis/SalesDataDash?publish=yes).

![image](https://github.com/user-attachments/assets/b5bc6701-ddab-49c1-890f-9a1b4af3b8a8)

## Insights Deep Dive
### Monthly Sales:

•	Despite having the worst monthly PRO in 2024, April had the second highest Average Online Purchase Price for all of 2024 at $190. This can be attributed to a spike in online sales of accessory Bags carrying an Average Online Purchase Price of $244 for April. The yearly PRO on Bags was 54% in 2024 but jumped to 62% in April. It was also our greatest revenue driver in April bringing in $26.7 million in online sales for the month, nearly double our second most popular product line for the month.

•	A large factor in poor online sales for April 2024 lies, predictably, in Rain Jackets. The PRO of Rain Jackets fell from a yearly average of 83% to 69% in April. With April being a typically rainy month,  it is hard to bear the convenience of purchasing a Rain Jacket in person when the need arises.

•	Overall, April was a tough month for online sales as Rain Jackets, Mercurial, Compression Wear, Accessory Bags, and Hats all fell short of our 70% PRO goal. Additionally, Backpacks, Therma-Fit tops, Vapor Cricket, Air Jordan, Tech Fleece tops, and Windrunners all failed to eclipse 60% PRO and represent significant areas for improvement.

•	While April was our worst month by PRO, August, September, October, and November all fell short of our 70% PRO goal as well. This shows a glaring seasonal weakness that can be addressed as PRO drops from 73.2% in July to 66.5% in August and only weakly crosses our PRO goal to 70.3% by December. 

![image](https://github.com/user-attachments/assets/2d9b5ea4-c078-4e0f-8bf4-b66f2c15bf9b)


### Regional Comparisons:

•	India, Japan, and Southeast Asia all areas of strength for online sales metrics. All three regions have a PRO over 70% and are our three best regions by Average Online Purchase Price with $194, $193, and $184 respectively which is at least $15 more than the next highest region. Japan is also our second strongest market for Total Online Revenue un excess of $188 million in 2024. However, India and Southeast Asia are our second and third worst performing regions by Total Online Revenue at $146 million and $155 million. Additionally, India had the lowest Total Units Sold Online with only 752,873 units.

•	Of 7 total regions, only 3 are below out 70% PRO goal, South Korea, Greater China, and America. South Korea has the strongest PRO of the group at 69.6%, barely missing our goal. South Korea is our second-best region by Total Units Sold Online with 1,039,464. However, with an Average Online Purchase Price of just $160, our lowest by any region, they generate only the third highest Total Online Revenue at nearly $167 million. This is just about $4 million more than America in 4th place and over $20 million behind second place Japan.

•	China provided incredibly strong Total Online Revenue at $209 million despite a 68% PRO. Interestingly, China has a Percentage of Units Sold Online of 68.9% which indicates a nearly 1% gap in online Unit Sales and online Revenue which would make sense given it has the second lowest Average Online Purchase Price at $161.

•	Our strongest overall region is Japan. Japan has a PRO of 71.6% despite having a Percentage of Units Sold Online of 71%. This can be attributed to their $193 Average Online Purchase Price, just $1 behind the leader India. However, their volume is far greater as Japan is the third best performing region in Total Units Sold Online at 971,982 and second in Total Online Revenue at $188 million. To quickly compare Japan to South Korea, as they are both second and third in Total Online Revenue and Total Online Units Sold: Japan's sales trailed South Korea's by around 70,000 units however Japan's Total Online Revenue exceeded that of South Korea by nearly $20 million with only a 2% difference in PRO.

![image](https://github.com/user-attachments/assets/bbfaa858-68da-4127-9d5e-278c845de24b)


### Online Product Offering Performance:

•	Cricket is our strongest product sub category by PRO with 74.8%. However, out of 11 categories, it is the 7th highest by Total Units Sold Online and 6th by Total_Online_Revenue. While the category may be a juggernaut in PRO, it lacks overall volume.

•	Acessories and Outerwear represent our strongest overall categories. They boast a 71.9% and 69.5% PRO while having also having the two highest Total Online Revenues at $189,817,968 and $187,340,930. Unsurprisingly, the volume for both products are the highest among categories with 1,126,725 and 964,819. 

•	The third best-selling category buy Total Online Revenue, Socks, boasts strong sales with $160 million in 2024 and has similarly strong Total Units Sold Online. However, Socks represent the second lowest PRO at only 67.2%. There are 35 individual product lines within the Socks subcategory. Just under 43% of the lines do not meet our PRO goal and nearly 26% do not break a PRO of 60%. The two top selling Sock product lines are the $300 Performance Socks and the $290 Crew Socks, they combine for nearly 10% of the Total Units Sold Online for Socks. Despite this, they have a PRO of 63% and 64% respectively. Performance Socks seem to have a pricing sweet spot for PRO in the $180-280 range as there are 7 products in this range and all have a PRO over 70% including 3 with a PRO over 80%.

•	The Football sub category leaves much to be desired. Despite having the third highest Average Online Purchase Price of $189, the remaining online sales number are abysmal. Football ranks dead last in PRO at 64%, Total Online Revenue  just under $42 million, and only 221,046 Total Units Sold Online. This is only 63% of the second lowest selling Total Units Sold Online. This is largely driven by two individual product lines. The $210 Phantom Vision and $230 Mercurial. These two lines represent nearly 30% of Total Online Revenue for football but have a 51% and 62% PRO respectively. 

![image](https://github.com/user-attachments/assets/66507613-9c59-4524-bfbc-b9f397a6d19a)


## Recommendations:

Based on the insights and findings above, we would recommend the Marketing and Sales teams to consider the following:

•	With the PRO drop in July (to 66.5%) and extended slump through November it may be worth trying a few online seasonal sales or deeper online discounts on seasonal items to boost PRO.

•	With the strength of the Chinese market and pure volume, a targeted ad campaign encouraging online sales to boost PRO from 68% to our goal of 70% would be very lucrative.

•	Re-evaluate the current marketing around online Football sub category sales, as the category is our weakest by every metric, beginning with the $210 Phantom Vision and $230 Mercurial. A boost in their PRO would help the category immensely as the two represent nearly 30% of all online Football product sales.

•	Consider a realignment of our Sock product line pricing, specifically Performance Socks. Our $300 Performance Socks are by far most popular, but may see a significant increase in PRO at the $280 price point given our current sales trends. This could be achieved either through a full realingement of Performance Sock pricing or an exclusive online sale to create a perception of greater value.

•	Consider a greater marketing presence in Southeast Asian and India, the two regions have exceptional PRO performance but lack the total volume to make them strong sales regions at present.

## Assumptions and Caveats:

Throughout the analysis, multiple assumptions were made to manage challenges with the data. These assumptions and caveats are noted below:

•	There is no indicative differentiation of products beyond the Product Line level. Because of this, Product Lines of the same Retail Price were assumed to be the same individual product.

•	Not every Product Line or Sub Category had sales data for every Month and Region. This was assumed to not be incomplete data but product rotations and offering changes. 

