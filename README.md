# User Profiling and Segmentation Analysis using Unsupervised Learning for Targeted Advertising

##### This project focused on leveraging data analytics and machine learning techniques to enhance targeted advertising strategies through comprehensive user profiling and segmentation. The primary goal was to gain deep insights into user behavior, preferences, and ad interactions to enable more personalized and effective marketing campaigns.

##### The project began with an extensive exploratory data analysis (EDA) of a rich dataset containing 16 diverse user attributes. These attributes included demographic information (age, gender, location, education level, income), online behavior metrics (time spent online, likes and reactions, followed accounts), device usage patterns, and ad interaction data (click-through rates, conversion rates, ad interaction time).

##### Key steps in the analysis included:

### 1. Data Preprocessing: 
##### Cleaned and prepared the dataset, handling any missing values and ensuring data quality.

### 2. Exploratory Data Analysis: 
##### Conducted a thorough examination of user attributes using various visualization techniques. This included creating distribution plots for demographic variables, analyzing device usage patterns, and investigating online behavior and ad interaction metrics.

### 3. Feature Engineering: 
##### Selected and transformed relevant features for the segmentation process, focusing on attributes most indicative of user preferences and behavior.

### 4. User Segmentation: 
##### Implemented a K-means clustering algorithm to segment users into distinct groups. The process involved:
#####  - Selecting a subset of features most relevant for segmentation
#####   - Applying appropriate preprocessing techniques (StandardScaler for numerical features, OneHotEncoder for categorical features)
#####   - Utilizing scikit-learn's Pipeline and ColumnTransformer for efficient data processing
######   - Clustering users into 5 distinct segments

### 5. Segment Analysis: 
##### Conducted in-depth analysis of each segment, calculating mean values for numerical features and modes for categorical features. This allowed for a comprehensive understanding of each segment's characteristics.

### 6. Segment Profiling: 
##### Assigned meaningful names to each segment based on their defining characteristics, creating profiles such as "Weekend Warriors," "Engaged Professionals," and "Budget Browsers."

### 7. Visualization: 
##### Developed an interactive radar chart using Plotly to visually compare the key features across different user segments. This visualization provided an intuitive way to understand the distinctions between segments.

##### The project yielded valuable insights for marketers:
##### - Identified distinct user segments with unique online behaviors and ad interaction patterns
##### - Revealed correlations between demographic factors and ad engagement metrics
##### - Highlighted opportunities for tailoring ad content and timing based on segment characteristics

##### The results of this analysis can be directly applied to optimize advertising strategies:
##### - Enabling more precise targeting of ads to specific user segments
##### - Informing decisions on ad content creation to resonate with each segment's interests
##### - Optimizing ad delivery timing based on each segment's online activity patterns
##### - Potentially improving overall ad campaign performance metrics such as CTR and conversion rates

##### This project demonstrates proficiency in data analysis, machine learning application, and data visualization techniques, as well as the ability to derive actionable insights from complex datasets for business applications.
