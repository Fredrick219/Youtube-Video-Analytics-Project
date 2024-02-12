### YouTube Channel Analysis Project

#### Objective:
The main goal of this project is to utilize the YouTube API to collect data from my YouTube channel and store it in AWS DBS. Subsequently, the collected data is analyzed to evaluate the performance of the channel's videos based on various metrics such as view count, like count, comment count, and more.

#### Data Overview:
The dataset comprises information on videos from my YouTube channel, including video ID, title, upload date, duration, publishing time, view count, like count, and comment count.

#### Data Analysis:
- **Target Variable:** The primary focus is on the `view_count`.
- **Data Spread:** The mean view count is satisfactory, but the wide standard deviation indicates a significant spread from the mean.
- **Correlation Analysis:** 
  - Strong positive correlation exists between `view_count` and `like_count`.
  - Weak negative correlation is observed between `title_length` and both `view_count` and `like_count`.
  - Moderate positive correlation is noted between `view_count` and `comment_count`.
  - The relationship between `video_duration_seconds` and engagement metrics is weakly negative.

#### Classification:
- Videos are classified into two categories:
  - **1:** Success
  - **0:** Failure
- The success rate is low, with only a small proportion of videos classified as successful.

#### Predictive Analysis:
- Utilized Random Forest Classifier, Logistic Regression, Support Vector Machine, Decision Tree Classifier, and K Nearest Neighbours.
- SVM emerged as the best-performing method with a best score of 0.956593.

#### Conclusion:
The analysis indicates a need for improvement in my channel's success rate. Successful videos exhibit exceptional performance, suggesting the potential for exponential growth with proper solutions. Encouraging viewers to like and comment on videos, along with engaging with comments and actively sharing content on social media platforms, are effective strategies to increase engagement and ultimately boost view counts. Additionally, collaborating with influencers and creators in my niche can help expand my reach and encourage cross-promotion, further enhancing engagement and visibility.
Furthermore, the analysis reveals a weak correlation between shorter video duration and title length with higher view counts. Although the correlation is not very strong, it suggests that viewers may prefer concise and to-the-point content, leading to increased engagement.
Identifying the keywords related to the street/hip-hop genre with the highest views suggests a strong interest from my audience in this particular genre. Capitalizing on this insight by creating more content within this genre aligns with my audience's preferences, potentially leading to increased engagement and higher view counts.

SVM is identified as the most effective method for predictive analysis. Leveraging these insights can contribute to the growth and success of my YouTube channel.
