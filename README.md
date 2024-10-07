# Customer-Feedback-Dashboard

### Dashboard Link: https://app.powerbi.com/view?r=eyJrIjoiMmJhMDM1NWItYTg4OS00ODY3LTg2ZTQtN2Q2NzQyNjliMThkIiwidCI6ImZlZTNiOTE2LTAxYzEtNDk4Ny1hNjQ2LWUxOTM0MzJiOWVhYSIsImMiOjl9

<img width="707" alt="Customer Feedback Dashboard" src="https://github.com/user-attachments/assets/5a782b25-709b-4a50-b0cd-c80566bd3189">

## Problem Statement

Objective: The aim of this project is to develop a Customer Feedback Dashboard for a hotel to analyze and visualize customer feedback data. The dashboard helps in tracking key metrics such as overall customer rating, NPS score, feedback on services, and demographic information. It offers insights into customer satisfaction and areas that need improvement, thus enabling better customer service and operational adjustments.

Context: Customer feedback is crucial for maintaining a high standard of service in the hospitality industry. Hotels rely heavily on feedback to assess the performance of their facilities and staff, as well as to improve their services based on real customer experiences. This dashboard simplifies the process of visualizing and understanding guest feedback, allowing management to take data-driven actions.

Problem: Manual analysis of customer feedback from various channels (e.g., booking sites, word-of-mouth, and online ads) can be tedious and time-consuming. Hotel managers need a comprehensive view of their feedback data to address service gaps and improve customer experience efficiently. Additionally, monitoring different feedback sources and demographic segments manually leads to delayed and inadequate decision-making.

# Solution

This Customer Feedback Dashboard provides a robust solution by offering:

- A holistic view of overall customer ratings, including an easy-to-understand visual representation of the hotel's average rating over time.
- Analysis of the NPS Score and NPS categories (Promoters, Passives, and Detractors) to gauge customer loyalty and satisfaction.
- Insights into the purpose of customer visits (business, vacation, functions, etc.) and gender distribution, helping in better customer segmentation.
- Visualization of feedback on specific hotel services (e.g., check-in process, gym, room service, staff attitude), enabling quick identification of strengths and weaknesses.
- Breakdown of feedback sources such as online bookings, word-of-mouth, and advertisements, to understand where most of the feedback is coming from.
- A trend analysis of feedback sources over the years (2020-2022), helping to identify shifts in customer engagement channels.

# Key Features

- Overall Rating: Shows the average customer rating with a star system (out of 5).
- NPS Score: Displays the Net Promoter Score (NPS) which measures customer loyalty.
- NPS Categories: Breaks down customers into Promoters, Passives, and Detractors, based on their feedback.
- Purpose of Visit: Pie chart visualization showing why customers visited (business, vacation, function, etc.).
- Gender Breakdown: Displays customer demographics by gender (male vs. female).
- Feedback Breakdown: Bar chart showing feedback for specific hotel services, like check-in process, gym, room service, and staff attitude.
- Source of Information: Visualizes how customers found out about the hotel, broken down by sources like online booking sites, word of mouth, etc.
- Source Trend: Displays the trend of feedback sources over the years (2020-2022).

# Data Sources and Tools

- Data Sources: Kaggle - Customer feedback collected from 2020 to 2022 through various feedback channels (booking sites, word-of-mouth, online ads, etc.).

Tools Used:
- Power BI: For creating visualizations and designing the dashboard.
- Excel: For organizing and cleaning the raw feedback data.
- DAX: To calculate metrics and KPIs like NPS score and customer segments in Power BI.

# Insights

A single page report was created on Power BI Desktop & it was then published to Power BI Service.

The Customer Feedback Dashboard provides the following key insights, which are essential for understanding guest satisfaction and identifying areas for improvement:

### [1] Overall Moderate Rating

    - The hotel’s average rating is 3.60/5, indicating that while customers are relatively satisfied, there is room for improvement, particularly in areas where customers may have had suboptimal experiences.
    - Maintaining a score above 4.0 should be a key target to ensure customer retention and positive word-of-mouth.
           
### [2] NPS Score Indicates Room for Improvement

    - The NPS score of 21.92 shows that there are more Promoters (926) than Detractors (499), but there is still a substantial portion of Passives (523) who are neither enthusiastic nor dissatisfied.
    - Increasing the proportion of Promoters can help improve loyalty and increase customer referrals. Attention needs to be given to converting Passives to Promoters by enhancing their experience. 
  
  ### [3] Majority of Visits are Business-Related

    - 42.51% of customers visited for business purposes, while 35.57% came for vacation. This suggests the hotel is catering more to business travelers.
    - Tailoring services and amenities to business guests (e.g., high-speed internet, conference facilities) could enhance customer satisfaction. However, there is also a significant opportunity to improve offerings for vacationers.

 ### [4] Gender Distribution is Balanced
 
    - The hotel caters almost equally to male (56.26%) and female (43.74%) customers, indicating that feedback trends aren't skewed by gender.
    - The hotel can focus on ensuring that services appeal equally to both genders without any specific bias.

### [5]  Room Service and Staff Attitude Receive High Feedback

    - Room service (7.0K feedback instances) and staff attitude (7.2K feedback instances) are two areas where the hotel received a higher volume of positive feedback.
    - These aspects can be considered strengths of the hotel and can be leveraged in marketing and promotional efforts.

### [6]  Word of Mouth and Online Bookings are Major Information Sources

    - 778 customers learned about the hotel through organizations, followed by hotel booking sites (306) and word-of-mouth (276).
    - Emphasizing partnerships with organizations and optimizing the hotel’s presence on booking sites could further drive customer traffic.

### [7]  Feedback Source Trends Show Growing Importance of Digital Channels

    - From 2020 to 2022, there has been a noticeable trend in customers relying more on hotel booking sites and internet advertisements.
    - Focusing on digital marketing strategies and increasing visibility on online platforms will likely enhance customer reach and feedback volume.

# Conclusion

The Customer Feedback Dashboard effectively centralizes all critical feedback metrics into a user-friendly format, enabling hotel management to quickly assess customer satisfaction, identify gaps in service, and track performance trends over time. This data-driven approach fosters better decision-making and customer experience optimization.
