# Web and Social Analytics
***Note: This project was completed as core assessment for the Web and Social Network Analytics module (2025/2026) at the University of Edinburgh. It utilizes simulated business scenarios to demonstrate proficiency in data-driven decision-making and social network theory***
<br><br>
In this project, I acted as a Business Analyst to provide data-driven insights for two distinct organizations: HighlandGear a large outdoor retailer and HaggisBus, a premier touring company. My objective was to apply social network analysis, recommendation systems and web traffic analytics to solve real-world business challenges.
The project is divided in two primary parts, combining theoretical framework with practical, code-based execution.

<br><br>
# Part 1: Retail Analytics (HighlandGear)
I performed a comprehensive analysis of HighlandGear’s transaction and referral data to optimize their marketing and loyalty strategies.

## Key Objectives
**Market Basket Analysis**: I used association rule mining to identify product bundles, calculating Support, Confidence and Lift to determine the most effective product associations.
**Referral Network Analysis**: I built a social network graph from customer referral data. By calculating Degree and Betweenness Centrality, I identified the top 5 most influential customers for targeted loyalty programs.
**Ethical Review**: I evaluated the privacy and fairness implications of network-based marketing, specifically addressing the risk of "echo chambers" in recommendation systems.

## Technologies Used
**Python**: NetworkX (for centrality measures) and Mlxtend (for Apriori/Association Rules).
**Data**: transactions.csv, referrals.csv.


<img width="950" height="659" alt="highlandgear_product_association_map" src="https://github.com/user-attachments/assets/6a881101-de1d-4067-8858-242fbb06f91f" />

# Part 2: Web Analytics (HaggisBus)
I analyzed a dataset of 160,000 visitors to the HaggisBus website to evaluate the effectiveness of their digital marketing campaigns.

## Key Objectives
<br><br>
**Campaign Performance**: I compared three paid advertisement campaigns (LinkedIn, Facebook, and Partner sites) using key metrics such as Conversion Rate, Bounce Rate and Session Depth.

<img width="1189" height="590" alt="haggisbus_marketting_channel" src="https://github.com/user-attachments/assets/3ffe67e8-f26f-4c1c-bfa4-5ac4e034dcff" />

**Platform & User Journey**: I investigated behavioral differences across platforms (Mac, Windows, iOS, Android) to identify technical or UX friction points in the user journey.

<img width="989" height="589" alt="desktop_vs_mobilehaggisbus" src="https://github.com/user-attachments/assets/cfc6231f-ae45-422b-8313-b7ca0d4dcc0d" />

**Traffic Source Comparison**: I benchmarked paid traffic against organic social, direct, and search engine traffic to understand varying levels of user intent.

<img width="946" height="529" alt="haggisbus" src="https://github.com/user-attachments/assets/239c9d6f-151f-40b7-b40d-8b2429d221a8" />

**Content Strategy**: I identified which blog content categories led to the highest conversions to guide future content investments.

## Technologies Used
**Python**: Pandas and Matplotlib/Seaborn for clickstream data processing and visualization.
**Data**: visitor_data_clickstream.csv.

## Deliverables
**Analytical Report**: A 1,298-word executive summary providing strategic recommendations based on the data.
**Codebase**: A Jupyter Notebook containing the data cleaning, network visualization and quantitative analysis.

## Based on my findings, I proposed:
**HighlandGear**: Specific product bundling strategies and a tiered loyalty program focused on high-centrality "influencers".
**HaggisBus**: Reallocation of marketing budget toward the highest-converting traffic sources and technical optimizations for underperforming mobile platforms.
