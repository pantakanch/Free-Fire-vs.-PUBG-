# Free Fire vs. PUBG Facebook Page Analytics

## Overview:

The "Free Fire vs. PUBG Facebook Page Analytics" project delves into the insights of the Facebook pages of Free Fire and PUBG, the leading battle royale games in Thailand. Utilizing Google Sheets and Supermetrics to gather and analyze data, this project aims to provide a comprehensive understanding of the engagement dynamics on these pages.


## Key Questions:

- How many posts does each page make?
- What is the overall engagement on each page?
- Which posts have the highest engagement?
- On which day does each page prefer to post the most?
- At what time does each page prefer to post the most?
- What types of content perform the best?


## Process:
**Data Collection:**
   - Utilize Supermetrics, a Google Sheets add-in, to gather data from Facebook Insights.

**Data Cleaning & Wrangling:**
   - Remove duplicates, trim whitespace.
   - Create additional columns:
     - Engagement: Sum of Reactions, Comments, and Post shares.
     - WEEKNUM: Week number of each post.
     - HOUR: Hour of the day when the post was made.
     - DAY: Day of the week when the post was made.
     - WEEKDAY: Numeric representation of the weekday (Monday as 1, Sunday as 7).

**Data Analysis:**
   - Utilize the cleaned data to create a pivot table for a more structured view.
   - Generate charts to visually represent key metrics.

**Dashboard Creation:**
   - Develop a dynamic dashboard using slicers for better interaction and visualization.


## Summary Insights:
![Screenshot 2024-01-27 193354](https://github.com/pantakanch/Free-Fire-vs.-PUBG-Facebook-Page-Analytics/assets/113978334/deb47f8f-3390-4aac-b0d2-2ef2822dab83)

Dashboard : https://docs.google.com/spreadsheets/d/1_dA50fkJpRbdFygU8ExY1YeVSeaQXdXAUIyalINyjng/edit#gid=1535441902

- Free Fire has a page with more likes than PUBG, with a ratio of 1.9 times.
- Free Fire has 300 posts, while PUBG has 247, indicating a 21.45% higher posting frequency for Free Fire.
- Free Fire shows an average engagement per post more than 3.75 times higher than that of PUBG.
- Free Fire prefers to post on Saturdays, but the highest engagement comes from Sundays. On the other hand, PUBG prefers to post on Wednesdays, but the best engagement comes on Sundays.
- Free Fire consistently posts during 8 am to 8 pm, with the best engagement occurring from 8 am to 9 am. PUBG prefers to post from 1 pm to 4 pm, but the best engagement comes at 8 pm.
- Update/Event is the content type leading in engagement for Free Fire, whereas PUBG performs best with Esports.


**Why Free Fire Appears Successful:**
Free Fire demonstrates a strong social media presence with 26.76 million page likes, a posting frequency of 54.9%, and an impressive average engagement of 4358 per post. The strategic posting times potentially align with its audience's preferences, as well as the diversity in content.


## Recommendations:
*For Free Fire:*
1. **Maintain Posting Frequency:** Continue the current posting frequency as it contributes to a higher engagement rate.
2. **Optimize Posting Times:** Focus on the optimal posting times, especially on Saturdays and Sundays when engagement is highest.
3. **Leverage Top Content Types:** Emphasize content types like Profile Media, Update/Event, and Promotion, ensuring diversity to keep the audience engaged.

*For PUBG:*
1. **Increase Posting Frequency:** Consider increasing the posting frequency to align more closely with Free Fire, maintaining audience interest and visibility.
2. **Optimize Posting Times:** Adjust posting times based on days with the highest engagement, particularly focusing on Sundays.
3. **Focus on Top-Performing Content:** Emphasize content types like Esports and Update/Event, and increase diversity of content.
