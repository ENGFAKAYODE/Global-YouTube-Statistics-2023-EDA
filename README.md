# Global YouTube Statistics 2023 - Exploratory Data Analysis
![image](you.jpg)

## TABLE OF CONTENT
- [GENERAL OVERVIEW](#general-overview)
- [OBJECTIVE](#objective)
- [SKILLS DEMONSTRATED](#skills-demonstrated)
- [DATA SOURCE](#data-source)
- [DATA TOOLS](#data-tools)
- [EXPLORATORY DATA ANALYSIS](#exploratory-data-analysis)
- [DATA ANALYSIS](#data-analysis)
- [INSIGHTS](#insights)
- [RECOMMENDATION](#recommendation)

## GENERAL OVERVIEW
The "Global YouTube Statistics 2023" notebook offers a comprehensive exploration of the dynamic landscape of YouTube in 2023 by delving into key performance indicators such as subscriber counts and video views. This project systematically examines the top YouTubers on the platform, visually presenting the distribution of subscribers through refined charts and box plots. It captures various dimensions of channel performance, from the sheer scale of viewership to the intricate correlation between subscribers and video views. By focusing on these metrics, the analysis not only highlights the channels that dominate the platform but also uncovers patterns that are critical for understanding how audience size directly impacts overall channel engagement.

## OBJECTIVE
The main goals of this analysis are to:
- **Identify Leading Influencers:** Pinpoint the top 10 YouTube channels by subscriber count to reveal who holds significant sway over global digital audiences.
- **Assess Channel Impact:** Investigate how viewership metrics correlate with subscriber numbers, providing insights into how a robust subscriber base can drive higher video views.
- **Uncover Growth Patterns:** Explore patterns and trends that signal audience engagement and channel performance, ultimately offering a framework to predict future success on the platform.
- **Drive Strategic Insights:** Equip content creators, digital marketers, and channel managers with actionable strategies by revealing the underlying data trends that influence channel growth and viewer retention.
- **Enhance Data Literacy:** Demonstrate the power of exploratory data analysis (EDA) through effective visualizations and statistical assessments, encouraging data-driven decision making in the rapidly evolving world of digital media.

## SKILLS DEMONSTRATED
- Exploratory Data Analysis (EDA)
- Data Visualization using Python libraries (e.g., Seaborn, Matplotlib)
- Data Cleaning
- Interpretation of data trends and correlations
- Critical Thinking.
- Data transformation

## DATA SOURCE
The analysis is based on a dataset of global YouTube statistics for 2023 on www.Kaggle.com
It contains 995 rows and 21 columns
![image](https://github.com/user-attachments/assets/994aba60-5dbc-4896-b191-7f2a5c1af9b4)

## DATA TOOLS
- **Jupyter Notebook** as the development environment.
- **Matplotlib** and **Seaborn** for visualization.
- **Pandas** for data handling and manipulation.

## DATA CLEANING STEPS
- Checked for nulls and found none
- Identified duplicate rows (Count = 0)
- Formatted column names (strip, replace, capitalize)

## DATA TRANSFORMATION
- Extracted and created a year column from "Created Date" column
- Corrected data type
- Checked for data quality (excluded rows with with "Created date" before Youtube launch
- Averged columns "Lowest Monthly Earnings" and "highest Monthly Earnings" to created a new column for better analysis

## EDA
- Top 10 Youtubers in terms of Subscribers
![image](https://github.com/user-attachments/assets/ebbab55f-c007-4b76-a80d-0b5b00443736)

- Top 10 Youtubers in terms of Views
![image](https://github.com/user-attachments/assets/f4f030b7-a6cf-46f6-8442-ccb3d5a47344)

- Does video views correlate with the number of subscribers?
  ![image](https://github.com/user-attachments/assets/7cb84436-0186-4ff4-b8e0-2a4d05c2c421)
- Is there a relationship between the number of video uploads and the number of subscribers or video views?
  <table> <tr> <th style="text-align:center">Subscibers</th> <th style="text-align:center">Video views</th> </tr> <tr> <td align="center"><img src="https://github.com/user-attachments/assets/e103061b-f961-45cf-90f3-9602fc617766" width="400"/></td> <td align="center"><img src="https://github.com/user-attachments/assets/95b75ddc-99bc-4d3e-bd02-c0ee1ff973f7" width="400"/></td> </tr> </table>
- Is there a relationship between Avg Estimated monthly Earnings and video views
![image](https://github.com/user-attachments/assets/56d080bb-0c8c-465d-b145-9a1fc6aed34c)
- Subcribers by category
![image](https://github.com/user-attachments/assets/994c3ed0-b456-4a81-9125-d86cc09e7821)
- Video views by category
![image](https://github.com/user-attachments/assets/538dd157-0802-414c-8f19-cb23120d60b0)
- Estimated Avg earning by category
  ![image](https://github.com/user-attachments/assets/fe1697ec-71bb-43dd-9225-8ae9a9cdd2e4)

## Factors affecting Avg Estimated monthly Earnings
![image](https://github.com/user-attachments/assets/3a631bc2-1c69-405e-81ab-46a8f1252b16)
Subscribers                       (42.5%),
Video Views                       (59.4%),
Uploads                           (16.4%),
Subscribers For Last 30 Days      (67.3%)

The two major variables highly correlated to Avg Estimated monthly Earnings are Video Views and subscribers. Uploads show very low correlation with Avg Estimated monthly Earnings.

## INSIGHTS
- "T-Series" is the most subscribed channel with 245M, followed by "Youtube Movies" with 170M
- "T-series" is the channel withe most video views with 228B, followed by "Cocomelon - Nursery Rhymes" with 164B
- Video Views and Subcribers are highly correlated. And Channels with more subscribers do have more views.
- No. of uploads shows a very low correlation with subcribers (0.08) and video views(0.17)
- Average Estimated monthly earnings correlates with video views, increase in video views led to an increase in Average Estimated monthly earnings
- Music & Entertainment leads with the most subscribers, video views and Average Estimated monthly earnings by Category
- The two major variables highly correlated to Avg Estimated monthly Earnings are Video Views and subscribers. Uploads show very low correlation with Avg Estimated monthly Earnings.

## RECOMMENDATION
1. **Leverage High-Performing Content Areas:** Since video views and subscriber numbers are highly correlated and channels with larger subscriber bases enjoy significantly more views, focus on strategies that amplify subscriber growth. Consider enhancing the quality of content, optimizing video SEO, and engaging your audience to convert viewers into subscribers.

2. **Benchmark Against Leading Channels:** With T-Series and YouTube Movies leading the charts in both subscribers and views, analyze their content strategy, posting frequency, and engagement tactics. This can inform best practices tailored for growth.

3. **Prioritize Quality over Quantity:** The number of uploads shows a very low correlation with both subscribers (0.08) and views (0.17). This indicates that the volume of content matters less than its quality. Allocate resources to create high-quality, engaging videos rather than focusing solely on increasing the number of uploads.

3. **Leverage Content Categories with High Earnings:**
The Music & Entertainment category leads in subscribers, video views, and estimated monthly earnings. For channels in this domain, reinforce content strategies that have proven to attract large audiences. For creators in other categories, consider incorporating elements that appeal to a broader or more engaged audience.

4. **Expand Audience Reach:** Collaborating with creators who have a strong subscriber base like "T-series", "Mr Beast" can help tap into existing, loyal audiences. This not only increases subscriber counts and views but can also provide new insights into effective content strategies.

5. **Re-assess Upload Frequency:** Since the number of uploads has minimal impact on growth and earnings, consider reallocating time and effort towards strategies that directly affect views and subscriber engagement, such as content quality and interactive audience initiatives.
