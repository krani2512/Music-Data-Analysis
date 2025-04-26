# Music-Data-Analysis

# Music Data Analysis Project Report

## Table of Contents

1. Introduction
2. Data Sources
3. Tools & Technologies
4. Data Cleaning & Preparation
5. Exploratory Data Analysis
6. Data Analysis
7. Results & Findings
8. Recommendations
9. Limitations
10. References

## Project Overview

This project analyzes YouTube music video performance data across various genres, artists, and time periods. By examining metrics like views, likes, dislikes, and engagement rates, the analysis provides insights into music consumption patterns and trends on YouTube. The project aims to identify popular genres, successful artists, and factors that contribute to high engagement on the platform.


## 1. Introduction

YouTube has become a central platform for music consumption worldwide, with music videos representing some of the most-viewed content on the platform. This analysis examines a dataset of popular songs across multiple genres to understand viewing patterns, engagement metrics, and trends over time. The insights from this analysis can help artists, record labels, and content creators optimize their strategies for YouTube.

## 2. Data Sources

The primary data source for this project is a CSV file containing information about music videos on YouTube. The dataset includes:
- Song titles and artists
- Album information
- Genre classification
- Release dates
- Performance metrics (views, likes, dislikes)

The dataset covers 100 songs across 10 different music genres, with release dates ranging from 1680 (classical compositions) to 2024. For each song, the dataset provides YouTube performance metrics as of April 2025.

## 3. Tools & Technologies

The following tools and technologies were used for this analysis:

- **Python**: Primary programming language for data analysis
- **Pandas**: Data manipulation and analysis
- **Matplotlib & Seaborn**: Data visualization
- **NumPy**: Numerical operations
- **Jupyter Notebook**: Interactive development environment

## 4. Data Cleaning & Preparation

The raw data required several preprocessing steps to prepare it for analysis:

1. **Date Conversion**: Transformed text-based release dates (e.g., "April 1, 2022") into datetime objects for time-based analysis
2. **Numeric Value Processing**: Ensured view, like, and dislike counts were stored as integers
3. **Feature Engineering**: Created additional metrics including:
   - Like-Dislike Ratio (likes divided by dislikes)
   - Engagement Rate ((likes + dislikes) divided by views)
   - Release Year (extracted from release date)
4. **Data Validation**: Checked for and addressed missing values, duplicates, and outliers

## 5. Exploratory Data Analysis

Initial exploration of the data revealed:

1. **Genre Distribution**: The dataset contains 10 different genres with approximately 10 songs each
2. **Temporal Coverage**: Songs span from classical compositions to recent releases in 2024
3. **View Count Range**: YouTube views range from 15 million (Lo-fi tracks) to over 8 billion (Latin hits)
4. **Engagement Metrics**: Engagement rates and like-dislike ratios vary significantly across genres

Visual exploration through histograms, scatter plots, and box plots provided initial insights into the distribution of key metrics and relationships between variables.

## 6. Data Analysis

The analysis focused on several key areas:

1. **Genre Performance Analysis**:
   - Calculated average views, likes, dislikes by genre
   - Compared engagement rates across genres
   - Analyzed like-dislike ratios as a measure of audience reception

2. **Temporal Analysis**:
   - Examined how view counts have changed over release years
   - Identified trends in engagement metrics over time
   - Analyzed the relationship between content age and performance

3. **Artist Analysis**:
   - Identified top-performing artists by total views
   - Analyzed artists with the highest engagement rates
   - Compared performance across different geographic regions

4. **Correlation Analysis**:
   - Investigated relationships between views, likes, and dislikes
   - Explored how release timing affects performance

## 7. Results & Findings

The analysis revealed several key insights:

1. **Genre Popularity**:
   - K-Pop shows the highest average view count per video, followed by Latin and EDM/Electronic
   - Hip Hop/Rap demonstrates the highest engagement rate, indicating an active audience
   - Classical music has the highest like-dislike ratio, suggesting high audience satisfaction

2. **Temporal Trends**:
   - Videos released between 2015-2020 have accumulated the highest view counts on average
   - Engagement rates have increased over time, with more recent videos showing higher audience interaction
   - Like-dislike ratios have become more polarized in recent years

3. **Artist Performance**:
   - BTS and BLACKPINK dominate in terms of total views
   - Artists with cross-genre appeal tend to have higher overall performance
   - Solo artists show different engagement patterns compared to groups/bands

4. **Engagement Insights**:
   - Videos with controversial content (indicated by high dislike counts) often have higher overall engagement
   - Music videos released alongside albums perform better than standalone singles
   - Videos with dance components tend to have higher view counts

## 8. Recommendations

Based on the analysis, the following recommendations can be made:

1. **For Artists and Labels**:
   - Consider incorporating K-Pop or Latin music elements to increase potential viewership
   - Prioritize audience engagement strategies for Hip Hop/Rap content
   - Include dance elements in music videos to boost view counts
   - Release music videos alongside albums rather than as standalone singles

2. **For Content Creators**:
   - Focus on high-production-value videos similar to those in the K-Pop genre
   - Create content that encourages active engagement (comments, likes/dislikes)
   - Consider collaborations across genres to access multiple audience segments

3. **For Platform Strategy**:
   - Target recommendation algorithms toward high-engagement genres
   - Feature content with dance elements prominently
   - Consider the high performance of controversial content when designing recommendation systems

## 9. Limitations

Several limitations should be considered when interpreting these findings:

1. **Sample Size**: The dataset contains only 100 songs, which may not be representative of all music on YouTube
2. **Selection Bias**: The dataset likely focuses on popular songs, missing insights from less-viewed content
3. **Temporal Limitations**: Older songs have had more time to accumulate views
4. **Genre Classification**: Some songs could belong to multiple genres, making classification imperfect
5. **External Factors**: The analysis doesn't account for external events that might influence video performance (awards, controversies, etc.)
6. **Platform Changes**: YouTube's algorithm changes over time may have impacted view patterns
7. **Regional Differences**: The analysis doesn't segment data by geographic region, which could reveal important patterns

## 10. References

1. YouTube Music Trends Report 2024
2. Digital Music Consumption Patterns (Industry Report)
3. Python Data Science Handbook (VanderPlas, J.)
4. Pandas Documentation: https://pandas.pydata.org/docs/
5. Matplotlib Documentation: https://matplotlib.org/stable/contents.html
6. Seaborn Documentation: https://seaborn.pydata.org/
