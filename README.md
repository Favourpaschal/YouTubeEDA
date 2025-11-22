# YouTubeEDA

This project explores a dataset of 537 YouTube videos to understand what drives engagement and popularity. The notebook analyzes video metadata, engagement metrics, categories, and publishing dates through statistical summaries and visualizations.

Overview

Key Features Analyzed:
view_count, like_count, comment_count, category_id, published_at, duration_seconds
(favorite_count was removed because it contained only zeros.)

The dataset contains no missing values.

Analysis Summary
Univariate Analysis

Views, likes, and comments are highly right-skewed.

Most videos are under 10 minutes, with a long tail of longer content.

Categories 24, 10, and 20 appear most frequently.

Many videos include captions.

Bivariate Analysis

Strong correlation between views and likes; moderate for views and comments.

Log–log scatter plots show clear linear trends in engagement.

Some categories show greater viral potential based on wider view distributions.

Time Series

Videos span multiple years with a mixed distribution across time.

Key Takeaways

Engagement metrics are strongly related.

Ratios like likes-to-views could improve modeling.

Category and video age help explain engagement patterns.
