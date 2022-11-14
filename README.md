# Team projects for graduate classes 

## Deep Learning - Sentiment Analysis for Amazon Product Reviews
• Classify customers’ attitudes (positive, neutral, or negative) toward a product based on their reviews with Natural Language Processing technique using PyTorch and Huggingface transformer

## [Big Data for Health - Classify Sleep Stages with Apple Watch Data](https://github.com/trantonnq/ClassifySleepStages)
- Built model to classify different sleep stages a person cycles through each night using readily available data from smart wearable devices in order to better understand their sleep quality. 
- Dataset were created by University of Michigan by collecting Apple Watch Health data and Polysomonography data of 31 subjects during their sleep.
- Preprocessed sampled health data (heart rate, motion, circadian, clock) with interpolation and Gaussian filter techniques to create useful features
- Applied different supervised learning algorithms such as Random Forest, Logistic Regression, K-Nearest Neighbors, Neural Net and AdaBoost and compared their performanced through metrics such as accurarcy and ROC curves. 

## Data Analytics and Visualization - Setlist Songs Recommendation and Visualization 
- This project is to analyze setlists of influential artists among different gernes in order to build visualization and recommendation tool that help artist select songs for their own setlist. 
- My role was to cleaned and transformed music data into useful features for visualization and clustering model.
  - Cleaned and joined data pulled from different sources: song names of each setlist are pulled from Setlist.FM, each song's low-level audio features are pulled from Spotify
  - Aggregated data to get summary statistics for each artist to be later used in clustering and visualization
  - Most of the data transforming and integration was implemented using Python pandas library because of its rich features and flexibility. However, due to the size of
the data, there was an issue with insufficient memory usage. This issued was later mitigated by using different methods of reducing memory usage such as processing
data in chunk, filtering out unimportant columns, and selecting appropriate data types for columns.

## Database Design - Build DBMS for a digital Corkboard site 
• Specified, designed, and implemented an image management system (a simplified version of Pinterest) using fully relational Database Management System, SQL, and PHP
