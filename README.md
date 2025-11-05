# PulseCare Marketing Insights - Project Overview
## The goal of this project is to investigate the performance of marketing campaigns at PulseCare in order to surface recommendations on marketing budget allocation across future campaign categories. 

**Founded in 2016, PulseCare is a medical insurance company serving over thousands of customers throughout the United States**. **In 2019, they launched a new set of marketing campaign categories** spanning topics like wellness tips, the affordability of their plans, and preventative care. Their customers can sign up for 4 different plans - bronze, silver, gold, and platinum - each with different premiums and claim coverage rates. 

Now that they’ve hired a new data team and are strategizing their marketing budget for the year, the company would like to build more understanding of the effectiveness of these campaign categories and how they relate to signups and subsequent patient claims. 
The budget is allocated to drive two primary objectives: 1) to increase the number of customer signups, and 2) to raise awareness of PulseCare’s brand across the country.

## Dataset Structure
The dataset consisted of three tables, including information about campaigns, signups and user demographics, as well as claims filed by customers and related claim information.

<img width="687" height="647" alt="ERD" src="https://github.com/user-attachments/assets/1640b4bc-7a5f-4381-9c41-5fb4bf1aa346" />

## Insights Summary
#### In order to evaluate campaign performance, we focused on the following key metrics:
- **Signup Rate**: The percent of people who see a campaign and subsequently sign up for a PulseCare plan. 
- **Cost per Signup**: The average dollars spent in order to acquire a signup from each campaign.
- **Click through Rate**: The percent of people who see a campaign and click on the associated link.

#### Signup Rate
- Across campaign categories, Health for All campaigns had the best-performing signup rate (2.9%) and the second-highest number of signups (3.5K).
- This high signup rate is due to the Health Awareness campaign type, which had by far the highest signup rate across all campaign types (3.72%).
- Interestingly, the category with the highest number of signups - #HealthyLiving - had a comparably low signup rate at 0.3%.

#### Click through Rate
- Across categories, Health for All and Benefit Updates performed nearly 3-4x better than the average CTR at 36% and 22%, respectively. 
- Within the two categories with high CTR, product promotion-based campaigns had relatively low CTR (0% and 7%).
- Family Coverage Plan had high impressions but no clicks - this needs to be investigated and could be due to missing data or issues with the campaign.

#### Cost per Signup
- Across campaign categories, Golden Years Security had by far the highest cost per signup ($124), as well as the lowest number of signups (23), compared to an average of $2.2.
- Within the two campaign categories with highest cost per signup, info-based campaign types (like offers and policy info) drove high costs per signup.
- Some COVID-based campaigns also had abnormally high CACs at $1.2-$1.3K.

## Recommendations
- **Health for All**: Reallocate budget from Golden Years Security, which has high cost per acquisition, to Health for All campaigns. The second category outperforms across all key metrics, yet we have invested a relatively low amount ($20K) on them.
- **Health Awareness**: Within Health for All campaigns, focus on health awareness-type marketing, and less on product promotion-type campaigns, which had low signup rate and CTR.
- **COVID Campaigns**: Investigate the cause of abnormally high cost per signup for COVID-based campaigns, which had 2 signups that costed over $1K, compared to an average signup cost of $2.2. Consider removing these campaigns altogether.
- **#HealthyLiving**: Decrease investment in this campaign category, which has the highest spend ($46K) but mediocre signup rates compared to Health for All campaigns.

## Dashboard
The dashboard can be found in Tableau Public [here](https://public.tableau.com/app/profile/adheesh.ghotikar/viz/PulseCareDashboard/Dashboard). This dashboard enables users to filter by plan, campaign type, and state, and focuses on trends and values in marketing metrics, signup metrics, and claim metrics.

<img width="683" height="859" alt="image" src="https://github.com/user-attachments/assets/3244794f-dd84-4bd0-ae32-15f7f756d2db" />


## Presentation Sample
The presentation created for the marketing team walks through the insights and recommendations above and can be found [here](https://docs.google.com/presentation/d/1x5WCuiCVZBY-iUbJbbaWycAb1RCtNAqX/edit?slide=id.p1#slide=id.p1). Some extracts are presented below for easy viewing.

<img width="1028" height="576" alt="image" src="https://github.com/user-attachments/assets/002d5075-1eaf-4f46-9eed-af0dbaddfabb" />
<img width="1036" height="576" alt="image" src="https://github.com/user-attachments/assets/634d4715-9ffb-4d35-a676-a9c27b953be6" />
<img width="1030" height="578" alt="image" src="https://github.com/user-attachments/assets/c60edfdf-e793-4118-a531-8007b01b93e5" />


