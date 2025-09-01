# Digital-Marketing-EComm-Donation-Analysis-FamilySpotlightCause
An animal shelter charity needs has an influx of litters and needs marketing efforts to support them.

(WIP)

## Executive Summary:
 A animal care charity is planning their next marketing campaign and needs to know what campaign types and creatives perform the best overall and especially with Family Spotlight cause to detemine where the advertising spend should be focused. Using Python and Tableau I extracted the data, deconstructed it into separate causes, joined it back to the marketing campaign data and visualized it in a dashboard.

### Recommendations:

1. Family Spotlight donations have not gained as much traction with Loyalty campaign types, and considering the focus on this cause group, I would recommend testing new creatives/messaging within the loyalty campaign to appeal to the family spotlight donors. Alternatively, advertising spend on this campaign could be diverted to Retargeting, Conversion and Engagement campaigns, which attracted more Family Spotlight donations. Because the highest average donations come from people who have visited the shelter within the last 3 months, I would recommend a campaign geared towards increasing shelter visits.
2. The creatives that drove the most donation revenue for Family spotlight causes were the "Kitty" Display ads (15K), "Smile" Display and "Cuddles" display.
3. Kitty and Smile creatives were most successful overall both bringing in over $19K of revenue and 50+ donations for Family Spotlight.

## Business Problem
The shelter is anticipating an influx of litters/families of animals and will need to focus their marketing efforts to drive donations to support them.

The donation purchase data is currently captured for each web transaction, which can include 1 or multiple types of donations/causes within each transaction.  The campaign performance data table can be linked to the donation purchase data using the transaction (Order) ID. To measure the performance of each donation type (Source), frequency (eg. Monthly, once etc) and targeted cause (eg. supplies or circumstance) I split out the causes and corresponding types, amounts and frequencies.

## Methodology
1.	I created 2 data sets: <br>

a.	Dataset for CleaningV2.xlsx <br>
A web transaction data set containing the donations in each purchase (and corresponding amount) and the order ID associated with that purchase. <br>
<br>
b.	Dataset for joiningV2.xlsx <br>
The second data set contains the digital marketing data to join back to the transaction, including the order ID. <br>
<br>
2.	A python algorithm to ensure that the transactions were split into their respective categories. A second algorithm to join the data back to the campaign data.<br>
<br>
3.	A Tableau dashboard to illustrate to the stakeholders the top performers and trends.<br>

## Skills
Microsoft Excel: functions, 'random' generators.
Python: Pandas, loops, functions
Tableau: data visualization, parameters, calculated fields 


## Results and Recommendations

The donation frequency of Family Spotlight donations is closely dispersed, with yearly subscriptions bringing in the most revenue, $28.1K * 12mths ($338.3K over the year - the revenue only accounts for the first payments), and 73 donations.
  In general, the population responded to the family spotlight cause group best for LeadGen campaign types, with the highest average donation ($503). Retargeting, LeadGen and Engagement Campaign Types performed best for donation revenue. The campaign that resonated least with the family spotlight cause group was loyalty campaign type, with only 7% of the total donations and lowest donation revenue ($5.8K) for the April to July time period. 

The audiences that the family spotlight cause group most resonated with is cart-abandons, Pet owners and vet-students by donation count and cart-abandons, Pet-owners and Philathropists for revenue volume.

The audiences who have the highest average donations to family spotlight causes are people who have visited the Shelter within the last 3 months and the philanthropist audience comprised of regular, high-income donors. 

#### Recommendations:
Revisit loyalty campaign parameters, perhaps the messaging or targeting can be adjusted to appeal more to Family spotlight donors.
For upcoming campaigns, boost ad spend into Retargeting, LeadGen and Engagement campaign types, building lookalike audiences from these campaigns. Test linking Supply cause groups with family spotlight cause groups to measure crossover.
To increase the Shelter-visit-3mths audience, I would recommend running a concurrent campaign to entice shelter visits.




