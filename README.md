
# 📹 YouTube Trending Videos Dashboard

The YouTube Trending Videos Dashboard offers detailed information on popular videos from ten different countries, providing insights into various aspects such as video performance, category distribution, and regional preferences.

The use of this dashboard enables Digital Communication and Marketing departments to define objectives for their YouTube campaigns, and maximize content distribution and creation initiatives.


## Data Source and Technology Stack

➡️ Data Source
- [Top Trending Videos YouTube 2021](https://www.kaggle.com/datasets/jyotmakadiya/top-trending-videos-youtube-2021)

🤖 Python Libraries
- numpy
- pandas
- os
- pycountry

📊 Visualization Tool
- Tableau

## Database Diagram
![Image]([http://url/a.png](https://github.com/DiegoBonilla39/ih_datamadpt0223_project_m2/blob/main/images/db_diagram.png))	
## Functional Design Mockup
## Dashboard Structure

### Main fields

**Average Trending Days**: The dashboard displays the average number of days that videos remain on the trending list both by country and category.
- 💡 Understand the duration of a video's trending duration and plan their promotional strategies accordingly.

**Avg. Minimum and Maximum Views and Interactions**: The dashboard presents the average minimum and maximum views and interactions (such as likes, dislikes, comments) received by trending videos. 
- 💡 Gauge audience engagement levels and assess the overall reach of videos in different markets and categories. 
- 💡 Define objectives and key performance indicators to measure campaign success

**Number of Videos by Category**: The dashboard showcases the total count of trending videos in each category. 
- 💡 Identify popular and trending content categories. 
- 💡 Prioritize content creation based on category demand.

**Category Distribution by Country**: The dashboard provides a breakdown of the trending video categories by country. 
- 💡 Identify regional preferences and tailor their strategies accordingly.

**Views and Interactions by Category**: The dashboard showcases the total views and interactions received by videos in each category. 
- 💡 Compare the performance of different content categories and identify trends in audience engagement.

### Filters
- 📅 Date
- 🗺️ Country
- 🔤 Category
## Main Conclusions

- Entertainment is the category with the most trending videos, but they don't have the longest duration as trends. However, it has a significant presence across the countries analyzed, with a focus on India.
- Music videos tend to remain as trends for a longer time, and they have a stronger presence in countries like Brazil, Canada, and France.
- Niche categories such as Sports, Auto, or Pets have a shorter duration as trends in general.
- Non-profit organization videos represent a trend that could be explored primarily in Germany.
- Russia seems to have less affinity towards YouTube based on the duration of trends, with a particular focus on political videos.
- User opinions are more evident through comments and dislikes in entertainment and music videos.

## Limitations

- Data for only 10 countries
- Data for only 1 month of 2021
- Data on video channels for further segmentation
