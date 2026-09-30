# social_media_engagement-Data-Analysis
Python-based analysis of 5,000 social media posts to uncover engagement trends across post types, content categories, countries, devices, sentiment, and user characteristics. The analysis was performed using Python, Pandas, NumPy, Matplotlib, Seaborn, and SciPy, with a focus on data cleaning, exploratory data analysis (EDA), statistical analysis, and visualization.

🎯 **Project Objectives**
- The main objectives of this project are to:
- Analyze social media engagement patterns.
- Identify differences in engagement across post types.
- Compare engagement across content categories and countries.
- Examine relationships between user demographics and engagement.
- Analyze the impact of device type and sentiment on engagement-related metrics.
- Investigate relationships between impressions, likes, watch time, followers, and engagement rate.
- Identify outliers and understand the distribution of engagement rate.
- Apply a log transformation to improve the distribution of engagement rate.
- Create visualizations to communicate analytical findings clearly.

Additional analytical features were created during the analysis:
- hashtag_count
- engagement_score
- engagement_rate_log

🛠️ **Technologies Used**
- Python
- Pandas – Data manipulation and analysis
- NumPy – Numerical operations
- Matplotlib – Data visualization
- Seaborn – Statistical visualization
- Google Colab / Jupyter Notebook

🔄 **Data Analysis Workflow**
The project follows a structured data analysis workflow:
- Data Import
- Data Type Conversion
- Missing Data Treatment
- Duplicate Check
- Data Standardization
- Data Validation
- Feature Engineering
    - Hashtag Count: The number of hashtags used in each post was calculated from the hashtags                        field.
    - Engagement Score: A weighted engagement score was created using:
                        Engagement Score = (Likes × 1) + (Comments × 2) + (Shares × 3)
- Outlier Analysis
- Distribution Analysis

📈 **Exploratory Data Analysis** 
The project analyzes social media performance from multiple perspectives:
- Post Type Analysis
- Country Analysis
- Demographic Analysis
- Device Analysis
- Sentiment Analysis

📊 **Visualizations**
The project includes several visualizations created with Matplotlib and Seaborn.
  * Matplotlib
    - Daily engagement trend
    - Posts by content category
    - Gender distribution
    - Likes vs. impressions scatter plot
  * Seaborn
    - Follower distribution across sentiment groups
    - Correlation heatmap
    - Post type distribution
    - Pair plot of numerical features
    - Engagement rate distribution
    - Log-transformed engagement rate distribution
  These visualizations help identify patterns, relationships, distributions, and potential anomalies in the dataset.

🔎 **Correlation Analysis**
A correlation matrix was created to examine relationships between numerical variables.
Some notable relationships from the analysis include:
 - impression_count and engagement_rate showed a negative correlation of approximately -0.23.
 - likes and engagement_rate showed a weak positive correlation of approximately 0.09.
 - age and engagement_rate showed an approximately 0.01 correlation.
These correlations describe associations within this dataset and should not be interpreted as evidence of causation.

💡 **Business Perspective**
This project can support social media performance analysis by helping analysts investigate:
  - Content format performance
  - Audience engagement behavior
  - Content category patterns
  - Geographic differences
  - Device usage
  - Sentiment-related engagement
  - Reach and impression patterns
  - Engagement-rate distribution
The analysis is descriptive and observational. Differences and correlations found in the dataset do not establish that a particular factor causes higher or lower engagement.
