# Row Health Marketing Campaign Performance Analysis


> Healthcare marketing campaign analysis using Excel and Tableau, evaluating signup rates, CTR, and cost efficiency across 11 campaigns to surface budget reallocation recommendations.



## Company Background 

Founded in 2016, Row Health is a medical insurance company serving thousands of customers throughout the United States. In 2019, they launched a new set of marketing campaign categories spanning topics like wellness tips, the affordability of their plans, and preventative care. Their customers can sign up for 4 different plans - bronze, silver, gold, and platinum - each with different premiums and claim coverage rates. 

Now that they’ve hired a new data team and are strategizing their marketing budget for the year, the company would like to build more understanding of the effectiveness of these campaign categories and how they relate to signups and subsequent patient claims. As a analyst contracting with Row Health, this analysis will be hinged on providing a dynamic visual deliverable to enable the marketing team to self-serve insights and regular-cadence reporting. The budget is allocated to drive two primary objectives: 1) to increase the number of customer signups, and 2) to raise awareness of Row Health’s brand across the country.


## Dataset Structure

The dataset consisted of three tables, including information about campaigns, signups and user demographics, as well as claims filed by customers and related claim information.


<img width="647" height="448" alt="image" src="https://github.com/user-attachments/assets/68ea0a6b-9941-432d-a926-97fb5ef2bd27" />


## Insights Summary

*The following sections diagnose each performance dimension in detail and close with prioritized recommendations.*


## North Star Metrics 

To evaluate campaign performance, the insights focused on the following key metrics:

- **Impressions**: The number of people who saw a marketing campaign.
- **Cost per Click (CPC)**: The amount an advertiser pays each time a user clicks on their advertisement
- **Click through Rate (CTR)**: The percent of people who see a campaign and click on the associated link. 
- **Signup Rate**: The percent of people who see a campaign and subsequently sign up for a Row Health plan
- **Cost per Signup**: The average dollars spent in order to acquire a signup from each campaign.


## Overall Performance Summary

- Row Health ran 11 campaigns from 2019–2023 generating **9 million** impressions at an average **CTR of 9.39%** and **CPC of $0.07**, suggesting campaigns were cost efficient and reasonably engaging. 

- However despite this efficiency, the overall **signup rate of 0.18%** and average **cost per signup of $3.70** indicates most campaigns struggled to convert reach into actual customers. 

- This conversion gap carried through to claims Row Health processed **$13.4 million** in total claims at an average of **$267**, with volume heavily concentrated among just 4 campaigns that dominated both signup and claim activity.

- Overall campaign performance was uneven, with a small number of campaigns driving the majority of business value while most underdelivered across every stage of the funnel.



## High Performers

**Key Insight:** Tailored Health Plans, Health For All, and #HealthyLiving consistently outperformed the rest across marketing, signups, and claims, making them the strongest candidates for increased investment.

- Tailored Health Plans showed the most balanced performance end-to-end. It delivered the highest reach at **1.39M impressions**, solid engagement and conversion, a below-average cost per signup **$4.70**, and the lowest average claim amount of **$209** among the top performers. Overall, it was the most stable and reliable performer.
  
- Health For All stood out for efficiency. Despite lower reach, it had the highest engagement with a CTR of **25%** despite the lowest impressions, and converted that into the most signups **3,545** and a signup rate of **2.08%** 12x the overall average at just **$1.20** per signup, the second most cost efficient campaign in the portfolio.

- #HealthyLiving combined strong reach at **1.37M** impressions with high signup volume **3,727**, a **0.27%** signup rate, and efficient costs $1.80 cost per signup, confirming consistent performance across both reach and conversion.

- Health For All and #HealthyLiving carry the second and third highest total claim amounts respectively, however their average claim amounts of **$231** and **$244** remain close to the portfolio average, suggesting their high signup volume does not come with disproportionate claim risk.

- These three campaigns drive the majority of value and offer the clearest opportunity for continued and expanded investment.




## Under Performers

**Key Insight:** Golden Years Security and six other campaigns consistently underperformed across every stage, using budget without generating meaningful customer value.

- Golden Years Security was the weakest overall. It had the highest CPC at **$0.68** nearly 9x the average combined with low impressions and below average CTR, limiting its reach from the start.

- This carried through to conversions, with the lowest signup volume and an extremely high cost per signup **$176.70**, nearly 7x the average. The lowest total claim amount of **$16,088** confirms that high costs and weak engagement never translated into meaningful customer acquisition at any stage of the funnel.

- Beyond this, six campaigns collectively produced fewer than **700** total signups at a median cost per signup of **$34.70**, nearly 9x the average. In short, they are spending money without driving customers.

- Shift budget away from these underperforming campaigns and reinvest in Tailored Health Plans, Health For All, and #HealthyLiving the campaigns that consistently deliver results across reach, conversion, and efficiency.

## Risk Campaign

**Key Insight:** Compare Health Coverage appears average on the surface, but drives the highest claim costs making it a potential profitability risk.

- The campaign delivered moderate results, with **660K** impressions, a signup rate of **0.42%**, and a cost per signup of **$3.60** all close to portfolio averages.

- However, the issue appears after signup. It has the highest average claim amount at **$410**, **54%** above average suggesting it attracts higher-cost customers. While conversion looks acceptable, the downstream cost may outweigh the value of those signups.

- Within Compare Health Coverage, Customer Testimonial campaign types drove the highest average claim amount at $499 nearly 2x the portfolio average suggesting the risk is concentrated in a specific campaign type, not the category as a whole.

- Refine targeting to attract lower-risk customers or reassess whether the campaign is profitable at its current spend.


## Recommendations

- **Invest in Top Performers:** Increase budget for Tailored Health Plans, Health For All, and #HealthyLiving these campaigns consistently drive the strongest results across reach, conversion, and efficiency.

- **Expand Health For All:** This campaign has the highest conversion and lowest cost per signup. Growth is limited by reach, not performance scaling it can unlock significant gains.

- **Optimize Compare Health Coverage:** While conversion looks solid, high claim costs ($410 avg) suggest profitability risk. Refine targeting or reassess spend before scaling.

- **Cut Underperformers:** Reallocate budget from Golden Years Security and six low-performing campaigns, which generate minimal signups at high cost.
Address Declining Signups: Signups have fallen since 2020. Focus investment on proven campaigns to stabilize and grow customer acquisition.

## Dashboard

The dashboard can be found in Tableau Public [here](https://public.tableau.com/app/profile/louis.ikponmwosa/viz/Row_health_dashboard/Dashboard3). This dashboard enables users to filter by plan, campaign type, and state, and focuses on trends and values in marketing metrics, signup metrics, and claim metrics.

<img width="1461" height="1866" alt="Dashboard 3" src="https://github.com/user-attachments/assets/209b43db-6aee-4638-87bd-8725fe42cf12" />


## Presentation Sample

The presentation created for the marketing team walks through the insights and recommendations above and can be found [here](https://docs.google.com/presentation/d/18EiCRds65iXUaX3kMb7JeYiMZ19gaBYmCU9kiOuspf4/edit?usp=sharing). Some extracts are presented below for easy viewing

<img width="950" height="530" alt="image" src="https://github.com/user-attachments/assets/4cd4fb8f-7303-498c-b3b0-bb24c85d9cad" />

<br><br>

<img width="950" height="530" alt="image" src="https://github.com/user-attachments/assets/128617e6-eaf7-4d5b-9531-8091b708e5c7" />

<br><br>

<img width="950" height="530" alt="image" src="https://github.com/user-attachments/assets/9aefca11-8880-40c9-a98c-1761d83d6b23" />

