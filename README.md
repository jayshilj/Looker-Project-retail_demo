# Looker-Project-retail_demo
Using Looker to demonstrate and analyse retail dataset

## What does this block do for me?

The retail application connects directly to your transaction-item-level table to deliver dashboards and insights that are useful to various teams in a retail organisation:
- Regional and store managers
- Merchandising and planning
- CRM and customer teams
- eCommerce teams
- Fraud detection for delivery

While it is reproducible on most databases, it is optimised for Google BigQuery. It uses **BigQuery nested tables** and partition/cluster keys to optimize performance, and **BigQuery Machine Learning** (BQML) to:
- create dynamic customer clusters based on their shopping patterns
- generate stock/sales predictions at the item-store-week level

The block delivers the following content:

### Group Overview dashboard

As a group VP or regional manager, quickly identify the group's overall performance, and the top/bottom stores and product categories driving this trend.

<img alt="Group Overview" src="https://github.com/looker/block-retail/blob/master/screenshots/group_overview_1.png?raw=true">

<img alt="Group Overview - Top movers" src="https://github.com/looker/block-retail/blob/master/screenshots/group_overview_2.png?raw=true">
<img alt="Store Deep Dive - Weather impact" src="https://github.com/looker/block-retail/blob/master/screenshots/store_deep_dive_1.png?raw=true">

<img alt="Store Deep Dive - Product impact" src="https://github.com/looker/block-retail/blob/master/screenshots/store_deep_dive_2.png?raw=true">


<img alt="Basket Analysis - Bundle promotion" src="https://github.com/looker/block-retail/blob/master/screenshots/item_affinity_1.png?raw=true">

<img alt="Basket Analysis - Product rationalisation" src="https://github.com/looker/block-retail/blob/master/screenshots/item_affinity_2.png?raw=true">
