# RowHealth Performance Report


> Analyzing 4 years of Row Health medical insurance data to diagnose and surface actionable growth levers using a dynamic visual deliverable.



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


## Marketing Insights

**Key Insight:** Despite overall cost efficient performance, Golden Years Security's CPC is nearly 9x the average with weak engagement, reallocating its budget toward #HealthyLiving offers the most scalable path to expanding reach cost effectively.


- Row Health ran 11 campaigns generating **9 million** impressions at an average CTR of **9.39%** and CPC of **$0.07** suggesting campaigns were cost efficient and reasonably engaging. However performance varied significantly across campaigns. 

- Tailored Health Plans and #HealthyLiving drove the highest reach at **1.39M and 1.37M** impressions respectively, but both performed near average on CTR, suggesting broad but unremarkable engagement. Health For All achieved the highest CTR at **25%** despite the lowest impressions, indicating strong creative resonance with a narrow audience. 

- On the other end, Golden Years Security significantly underperformed with the highest CPC at **$0.68**, nearly 9x the average, combined with low impressions and below average CTR, suggesting poor cost efficiency and weak audience fit. 

- Row Health should consider reallocating Golden Years Security budget towards #HealthyLiving due to its balance of strong engagement and cost efficiency. #HealthyLiving combines one of the highest proven reach at 1.37M impressions with a below average CPC which offers the most cost effective path to expanding audience without sacrificing efficiency.



## Signup Insights

**Key Insight:** Signup performance was heavily concentrated among a few campaigns, with Health For All and #HealthyLiving consistently outperforming across conversion and cost efficiency while a steady post-pandemic decline in signups since late 2020 signals an urgent need to reallocate budget away from the six underperforming campaigns and toward proven high converting campaigns before the trend worsens.

- From 2019–2023 Row Health generated **16,338** total signups at an average signup rate of **0.18%** and cost per signup of **$3.70**. While cost efficiency was reasonable overall, the low average signup rate indicates most campaigns struggled to convert impressions into actual customers.

- Signup activity spiked sharply in early 2020 across all campaigns, most notably among the top performers, likely driven by pandemic related demand for health coverage. Since late 2020 signups have steadily declined across all campaigns, returning to and falling below pre-pandemic levels, signaling an urgent need to reinvest in high converting campaigns before the trend worsens.
  
- Health For All stands out as the single most effective campaign in the entire portfolio. Despite having the lowest impressions in marketing, it generated the highest signup count at **3,545** and a signup rate of **2.08%**, 12x the overall average. At **$1.20** per signup it is also the second most cost efficient campaign. This combination of high conversion and low cost makes it the strongest case for increased investment and expanded reach.

- #HealthyLiving reinforces the marketing recommendation **3,727** total signups, a **0.27%** signup rate, and **$1.80** cost per signup confirms it delivers consistent performance across both reach and conversion, making it the most well rounded campaign in the portfolio.

- On the other end, 6 of 11 campaigns collectively failed to generate meaningful signup volume, combining for fewer than **700** total signups at a median cost per signup of **$34.70**, nearly **9x the average**. These campaigns are consuming budget without producing customers.

- Golden Years Security was the worst performer across both marketing and signup metrics, the lowest signup count, a cost per signup of **$176.70** nearly **7x the average**, and consistently weak engagement at every stage of the funnel. There is no metric that justifies continued investment at current budget levels.





## Claim Insights

**Key Insight:** While high performing signup campaigns naturally drove the highest claim volumes, Compare Health Coverage presents the most significant profitability concern, generating the highest total and average claim amounts despite only average signup conversion, suggesting it attracts high utilization customers that may cost Row Health more than they generate in value.

- From 2019–2023 Row Health processed **$13.4 million** in total claims at an average claim amount of **$267**. Claim volume was heavily concentrated among the top 4 campaigns, Compare Health Coverage, Health For All, #HealthyLiving, and #CoverageMatters which together accounted for the majority of total claims, directly mirroring their dominance in signup volume.

- Claim amounts were relatively flat from 2019 through early 2021, then rose sharply beginning in Q2 2021 among the top performers, likely reflecting delayed post-pandemic healthcare utilization as people resumed elective and routine care. Since late 2023 claim amounts have steadily declined, suggesting utilization is normalizing.

- Compare Health Coverage stands out as the most concerning campaign from a profitability standpoint it carries the highest average claim amount at **$410**, which is 54% above the portfolio average of **$267**, despite only average signup conversion. This suggests the campaign may be disproportionately attracting high utilization customers.

- Health For All and #HealthyLiving — the two campaigns recommended for increased investment — carry the second and third highest total claim amounts respectively. However both maintain average claim amounts of **$231** and $244, remaining close to the portfolio average, suggesting their high signup volume does not come with disproportionate claim risk.

- Tailored Health Plans presents the most balanced profile across all three sections strong signup conversion, below average cost per signup, and a controlled average claim amount of **$209**, the lowest among the top performers. This consistency across marketing, signup, and claim metrics makes it the most defensible investment recommendation in the entire portfolio.

- Golden Years Security continued its pattern of underperformance generating the lowest total claim amount at **$16,088**, confirming that its high cost per signup and weak engagement never translated into meaningful customer acquisition or business volume at any stage of the funnel.


## Recommendations


## Dashboard

The dashboard can be found in Tableau Public here. This dashboard enables users to filter by plan, campaign type, and state, and focuses on trends and values in marketing metrics, signup metrics, and claim metrics.

## Presentation Sample

## 
