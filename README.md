# Google_Advanced_Data_Analytics__Course_5_Project__TikTok_Regression_Analysis

In the previous stage, it was determined that 'verified_status' has a relationship with whether or not a user will post a video containing an opinion. Specifically, it was observed that verified users are more likely to post opinion videos compared to claim videos.

The distribution of many variables, particularly those related to video metrics, was visualized, and most were highly right-skewed.

The outcome variable 'verified_status' exhibited significant class imbalance; therefore, the minority class, 'verified', was upsampled.

Due to high multicollinearity, the variable 'video_like_count' was dropped, and categorical variables were encoded using one-hot encoding.

After fitting and evaluating the model, the following scores were obtained: Precision: 61%, Recall: 85%, F1-Score: 71%, and Accuracy: 65%. Although the model's precision is only satisfactory, the recall score is quite good. The accuracy score is also on the lower end of what is generally considered acceptable. 