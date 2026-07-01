Project Overview:

A company runs campaigns across realstate and other metrics. For different campaigns leads are from multiple sources contacted AI powered voice bots.Based on conversations bot seperated the leads into different categories like Qualified, IntentQualifies, Disqualifies etc.... The objective of this project is to identify the Best Performing Sources, Performance breakdown of each source across campaigns, Deep Analysis of Source 5 to identify patterns that contribute to the sucess for source 5, Campaign Specific Analysis to understand what worked and what didn't worked for specific campaign and Automation.

Business Outcomes:

---> Analyze Best performance sources
---> Performance Breakdown of sources across campaigns
---> Source 5 Deep Analysis to find attributes
---> Campaign Specific Analysis

Dataset:

Campaign_data - Details of leads contacted across all campaigns and include all status
Campaign_souce - Each lead which source it came from
Campaign_to_Source5 - It gives detailed metadata of leads from source 5 that are used in campaign
QL_data - Subset of campaign data contains only leads status marked as Qualified or Intent Qualified
QL_to_Source - Source and category where applicable for each qualified lead
QL_to_source 5 - Detailed fields for qualified leads from source5

Tools Used:

Power BI
Power Query
DAX
SQL
Excel

 1.Best Performing Source And Performance Breakdown
 ![iamge alt](https://github.com/Renuka-1122/Campaign_Performance_Analysis-PowerBI/blob/5faba98cd0325df40b007a7955a4d55945aea61f/Performance%20Breakdown.png)

 Total leads, Qualified leads and conversion are the key KPI's. Column chart is plotted between Sources and conversion rate to find best performing Source. Source2 had high  conversion rate compared to other sources. Matrix visuals is plotted for performance brakdown of each source across all campaigns.Source , Campaign code and lead status  are slicers to filter the visuals.

 2.Source 5 Deep Analysis
 ![image alt](https://github.com/Renuka-1122/Campaign_Performance_Analysis-PowerBI/blob/a84e96ceb759b1464f71f7a4fb1799d48fbaab35/Source%205%20Deep%20Analysis.png)
 
 Total leads, Qualified leads, Conversion rate KPI's are plotted for Source5. Bar chart is plotted between top 10 cities and conversition rate. City Thumakuru has best      conversion rate and Benguluru has low conversion among top 10 cities. Column chart is plotted between Total leads and credit score. More amount of leads are from people who have more than 700 credit score. Column chart is plotted between Age band and credit card utilization. People age between 50-54 are using more credit cards. 

 3.Specific Campaign Analysis

 ![image alt](https://github.com/Renuka-1122/Campaign_Performance_Analysis-PowerBI/blob/d217e3579bb4107b5df4cbe1f1297a5f5c4a77be/Specific%20Campaign%20Analysis.png)

 For Dean campaign total leads, qualifies leads, conversion rate KPI's are plotted. Bar chart is plotted between total leads and sources. Source 2 had more leads foe dean campaign. Conversion rate across different sources plotted in column chart. And Lead status distribution is plotted in Donut chart. Follow up status had more percentage.

 Key Insights:
 
 --> Source 2 has Best Conversion rate compared to other sources.
 --> Age band between 50-54 has more credit utilization
 --> Dean campaign performs best than other campaigns
 --> Higher credit score bands contained the largest share of Source5 leads.
 
 







