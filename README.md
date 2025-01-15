# 预测Up主日增指标数据

线性模型预测Up主除去充电指标以外的7个指标的日增量，包括日增播放量、日增粉丝、日增点赞、日增收藏、日增硬币、日增评论、日增弹幕、日增分享。

特征为前XX天的日增量，XX建议为7天一个周期。由于B站提供的数据量只有三个月，预测误差较大，但整体趋势近似，如果有更大的数据量（比如一年以上的数据），拟合效果应该会更好，当然前提是这个uploader的视频更新节奏不变，视频质量也没有较大差异。

# **Predicting Daily Incremental Metrics for Content Creators**

Using a linear model, we aim to predict the daily increments of seven metrics for a content creator, excluding the “charging” metric. These metrics include daily increments of views, followers, likes, favorites, coins, comments, bullet chats, and shares.

The features are the daily increments over the past XX days, with XX recommended to be a 7-day cycle. Due to the limited data availability (only three months of data provided by Bilibili), the prediction error may be relatively large. However, the overall trend is expected to be approximate. With a larger dataset (e.g., over a year), the fitting accuracy would likely improve, provided that the uploader’s video release schedule remains consistent and the video quality does not undergo significant changes.
