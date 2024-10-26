# Movie Correlation Analysis Project

This project explores correlations within a movie dataset, analyzing relationships between variables such as ratings, genres, budgets, box office gross, runtime, and more. Using Python libraries for data analysis and visualization, the project identifies significant insights that help understand the factors contributing to movie success. The libraries used are pandas, numpy, seaborn and matplotlib. 

## Project Structure
Data Preparation: Load and preprocess the dataset to ensure data quality (handling missing values and setting up data types).
Exploratory Data Analysis (EDA): Visualize distributions and trends to understand the dataset’s structure, identifying relationships between budget, ratings, gross earnings, etc.
Correlation Analysis: Use correlation heatmaps and scatter plots to analyze the relationships between key numeric variables.

## Key Graphs and Descriptions
**Correlation Heatmap:** Shows the correlations between various numerical variables, such as budget, gross earnings, and runtime. Higher positive values indicate stronger relationships, helping identify which factors might contribute most to a movie’s financial success.

**Budget vs. Gross Scatter Plot:** Plots budget against gross earnings to visualize how investment correlates with revenue. A positive trend would suggest that higher budgets are generally associated with higher gross earnings.

**Genre Distribution:** A bar chart displaying the distribution of movie genres in the dataset, providing insights into the genre diversity of the sample and allowing genre-specific analysis of factors like ratings and gross.

**Rating vs. Gross Box Plot:** Illustrates how different MPAA ratings (G, PG, PG-13, etc.) relate to box office gross. This graph provides a view of how audience restrictions might affect financial performance.

**Yearly Gross Trend Line:** Shows the trend of gross earnings over time, highlighting how the movie industry’s revenue potential has changed and evolved across years.

## High Correlations Observed
The correlation analysis reveals several significant relationships, with the highest correlations listed below:

Variable Pair & Correlation
Gross & Votes: 0.614751
Budget & Gross: 0.740247
YearCorrect & Released: 0.996181
Other Identical Fields: 1.000000

**Conclusions:**

Votes and Budget have the highest correlation to Gross Earnings, indicating that higher budgets and more votes are strongly associated with better financial performance.
Company has low correlation with gross earnings, suggesting that studio association may not be as critical to financial success.

