# Coffee-Shop-Marketing-Analysis

## Overview
This project analyzes customer behavior and promotional effectiveness for **Maven Cafe's rewards program**. Using a Tableau dashboard and story, we explore key customer segments, average customer value, and offer performance to identify opportunities for targeted marketing strategies.

The analysis uses three key datasets:

1. **Customers Data**: Contains demographic information (such as age, gender, and income) and rewards membership details of customers enrolled in the Maven Cafe Rewards program.
2. **Events Data**: Captures customer interactions over a 30-day period, including transactions, offers received, viewed, and completed. This dataset helps track the effectiveness of various promotional offers.
3. **Offers Data**: Provides details about different types of promotional offers (e.g., BOGO, discount, informational) sent to customers, along with their duration and characteristics.

These datasets were taken from Maven Analytics website and then merged in python and analyzed to identify key customer segments, evaluate offer performance, and develop data-driven strategies for future promotional targeting.

## Analysis

This project evaluates several key metrics to understand customer behavior and the effectiveness of promotional offers in the Maven Cafe Rewards program. 
The primary metrics include:
1. **Conversion rate** (the percentage of customers who completed an offer after viewing it), click-through rate (CTR) (the percentage of customers who viewed an offer after receiving it)
2. **Average customer value (ACV)** (the average revenue generated per customer).
3. **Conversion rate** (the percentage of offers completed after being viewed)
This metrics helped identify high-engagement segments and determine which offers perform best across different customer demographics, including age, income, and gender.

## Interactive Dashboard

The **Marketing Performance Dashboard** provides an interactive view of key metrics related to customer behavior and offer performance. It includes:

- **Conversion Rate and Click-Through Rate** for different offer types (BOGO, discount, informational).
- **Customer Segmentation** by age, income, and gender, highlighting high-performing and underperforming groups.
- **Time-Based Trends** showing the number of offers received, viewed, and completed across the month.
- **Channel Performance** to determine which marketing channels are driving the most engagement.
- **Average Customer Value** across different segments, providing insights into customer profitability.

[Access the Dashboard here](https://public.tableau.com/views/CoffeeShopMarketingAnalysis_17253757041670/Dashboard1?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
![image](https://github.com/user-attachments/assets/4d7b5c41-3351-416c-a60b-bb551f34f954)



## Tableau Story

The **Maven Coffee Shop Marketing Analysis** guides the viewer through key insights discovered during the analysis:

- **Key Customer Segments to Target and Improve**: Highlights the most valuable customer segments and those that require improvement based on conversion and engagement metrics.
- **High Engagement, Low Conversion Segments**: Identifies segments with high click-through rates but low conversion rates, suggesting areas for optimization.
- **Offer Effectiveness**: Shows which offers are driving the high conversion and which need adjustment.

<div class='tableauPlaceholder' id='viz1725379320526' style='position: relative'><noscript><a href='#'><img alt='Maven Coffee Shop Marketing Analysis ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;DF&#47;DFTTPBP5Z&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='path' value='shared&#47;DFTTPBP5Z' /> <param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;DF&#47;DFTTPBP5Z&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-GB' /><param name='filter' value='publish=yes' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1725379320526');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='1016px';vizElement.style.height='991px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>


