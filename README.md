# Netflix Dataset Exploratory Data Analysis

## Project Overview
This project performs Exploratory Data Analysis (EDA) on the Netflix titles dataset to understand content distribution, trends, and patterns available on the streaming platform. The analysis provides insights into the types of content, release patterns, genre distributions, and other key characteristics of Netflix's library.

## Dataset Description
The dataset contains information about movies and TV shows available on Netflix, including:
- Title
- Type (Movie/TV Show)
- Director
- Cast
- Country
- Release year
- Rating
- Duration
- Listed genres
- Description

## Tools & Libraries Used
- Python 3
- Pandas - Data manipulation and analysis
- Matplotlib - Visualization
- Seaborn - Statistical data visualization
- WordCloud - Text visualization

## Analysis Performed

### 1. Data Overview and Summary Statistics
- Examined basic dataset structure and information
- Generated summary statistics for numerical and categorical variables
- Identified missing values across different features

### 2. Missing Data Analysis
- Visualized missing data patterns using heatmaps
- Quantified missing data percentage in each column

### 3. Content Distribution Analysis
- Analyzed the distribution of movies vs. TV shows
- Explored content rating distribution across different categories

### 4. Temporal Analysis
- Examined content release trends over time
- Identified periods of increased content production

### 5. Genre Analysis
- Identified top 10 most frequent genres on Netflix
- Explored genre distribution across content types

### 6. Title Analysis
- Created word cloud visualization of Netflix titles
- Identified common themes and keywords in content naming

## Future Work
- Perform sentiment analysis on content descriptions
- Analyze relationships between genres, ratings, and content popularity
- Explore regional content distribution and preferences

## How to Use This Repository
1. Clone this repository
2. Install required libraries: `pip install pandas matplotlib seaborn wordcloud`
3. Run the Jupyter notebook: `jupyter notebook netflix_eda.ipynb`

## Author
AFNAN SAIF M S

## Acknowledgments
- Dataset source: https://www.kaggle.com/datasets/shivamb/netflix-shows
