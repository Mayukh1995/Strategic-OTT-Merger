# Strategic Merger: LioCinema & Jotstar
## Project Overview
Lio, a leading telecommunications provider in India, is merging with Jotstar, a prominent streaming platform. This strategic alliance aims to combine LioCinema’s vast subscriber base with Jotstar’s rich content library to revolutionize the digital streaming landscape in India.
Despite their individual strengths, both platforms face challenges in user retention, engagement, and revenue optimization. To address these, the merged entity aims to leverage Power BI for advanced analytics, facilitating data-driven decision-making across content strategy, subscriber growth, and revenue streams.

Explore the live dashboard: [View Here](https://app.powerbi.com/view?r=eyJrIjoiZWYzODg1NTctODUwYi00ZmYwLWFjNjItNDEwNTgzNjgzMGQ3IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

Here is my presentation link:[Click Here](https://youtu.be/OLOsulZdI2g)

# Datasets:
Understanding the datasets was crucial to generate actionable insights. The project utilized multiple tables:
Jotstar_db: 
           contents : content_id,content_type,language,genre,run_time. (Static Details)
           subscribers : user_id,age_group,city_tier,subscription_date etc.(Transactional Data)
           content_consumption : user_id,device_type,total_watch_time. (Static Details)
Liocinema_db
           contents : content_id,content_type,language,genre,run_time. (Static Details)
           subscribers : user_id,age_group,city_tier,subscription_date etc. (Transactional Data)
           content_consumption : user_id,device_type,total_watch_time. (Static Details)

# Importing Data and Data Modeling:
Data was imported from MySQL into Power BI, followed by cleaning and transformation steps. Proper data modeling was essential to ensure accurate insights and smooth report performance.
We followed a **Star Schema**, structuring data into dimension and fact tables for better query performance and data integrity.
![](https://github.com/Mayukh1995/Strategic-OTT-Merger/blob/main/Data%20model%20OTT.PNG)

# Power BI Dashboard Overview:
The dashboard comprises six pages for different stakeholder needs:

**1. Home Page: A landing page with problem overview and navigation.**
 ![](https://github.com/Mayukh1995/Strategic-OTT-Merger/blob/main/Landing%20page%20OTT.PNG)

**2. Content Analysis : Gives detailed comparison of content types across both platforms.**
 ![](https://github.com/Mayukh1995/Strategic-OTT-Merger/blob/main/Content%20Analysis.PNG)

**3. Subscriber Insights : Analyzes trends in subscriber acquisition and demographic variations.**
![](https://github.com/Mayukh1995/Strategic-OTT-Merger/blob/main/Subscriber%20Insights.PNG)

**4. Activity Analysis :Shows patterns of activity across age groups, city tiers, and subscription plans.**
![](https://github.com/Mayukh1995/Strategic-OTT-Merger/blob/main/Activity%20Analysis.PNG)

**5. Upgrade Insights : Provides insights into subscription upgrades and their influencing factors.**
![](https://github.com/Mayukh1995/Strategic-OTT-Merger/blob/main/Upgrade%20Insights.PNG)

**6. Downgrade Insights : Analyzes of subscription downgrades and associated trends.**
![](https://github.com/Mayukh1995/Strategic-OTT-Merger/blob/main/Downgrade%20Insights.PNG)

**7. Revenue Analysis : Patterns in total revenue  across months, platform, city tiers etc.**
![](https://github.com/Mayukh1995/Strategic-OTT-Merger/blob/main/Revenue%20Analysis.PNG)

# Skills Developed:
## Power BI Fundamentals:
Power BI Fundamentals:
1. DAX measures and calculated columns
2. Page navigation with bookmarks\
3. Tooltips to enhance user experience
4. Data Modeling & Validation - Creating relationships between tables
5. Power BI Service: Publishing and sharing dashboards

## Tech Stacks:

1. MySQL (Data extraction and transformation)
2. Power BI Desktop (Report building and analysis)
3. DAX language (Custom calculations and logic)
4. M language (For advanced transformations)
5. OBS Studio (For video presentation)

##  Business Related Terms:

1. Active/Inactive Rate
2. Upgrade & Downgrade Rate
3. ARPU (Average Revenue Per User)
4. Churn Rate
5. Watch Time & User Engagement
6. Tier-wise User Distribution

## Soft Skills:

* Business domain knowledge in telecom and OTT streaming.
* Strategic thinking for content and marketing optimization
* Audio Visual Presentation

 # Conclusion:

This project empowers the newly merged platform to make informed decisions using data. By understanding subscriber behavior, content preferences, and revenue dynamics, Lio-Jotstar can refine strategies to become the leading OTT platform in India. The insights derived serve as a roadmap to enhance customer satisfaction, boost engagement, and maximize profitability.













