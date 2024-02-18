# LISA-PHASE-1-PROJECT
# MOVIE GENRE ANALYSIS FOR MICROSOFT
# AUTHOR:LISA MWIKALI
## Project Overview

The project aimed to guide Microsoft's entry into the entertainment industry by conducting a comprehensive analysis of current box office trends. The business problem was to provide actionable insights for the decision-making process regarding the type of films Microsoft's new studio should create. The data utilized for this analysis consisted of movie title, genres, domestic gross and foreign gross for movies made, year of release, studios, run time in minutes, average rating for different movie titles, number of votes and other relevant factors sourced from imdb database .

## Business Problem
The business problem revolves around Microsoft's entry into the entertainment industry with the establishment of a new movie studio The main pain points include the need to make informed decisions about the type of films the studio should create to maximize success? I picked the data analysis questions by thinking about what knowledge Microsoft might need to have, being that they are new to the movie game. The data questions aim to address key aspects crucial for strategic decision-making in this context.

## Data Understanding
The sample includes a diverse set of movies, spanning various genres, gross, release dates and ratings. It represents a cross-section of the industry to provide insights into broader trends and patterns. The primary target variables are "domestic_gross" and "averagerating" which will serve as the measure of a movie's success.
Dropping Variables with Null Values and removing outliers
Variables Dropped: studio, domestic_gross, foreign_gross, run_time in minutes, genres I chose to drop this variable because they are crucial for the analysis and they contained null values. Removing rows with missing values in these key variables ensures the integrity of the analysis, as imputing critical financial and content-related information may introduce inaccuracies especially considering I plan to use the columns for my visualizations. I then used the IQR method to address outliers in the variable "domestic_gross”. My reason was because the outliers might distort the assessment of the movie's rating, and addressing them ensures a more accurate representation of the central tendency.

## Top 10 Genres by Average Rating:
The bar plot displaying the top 10 genres with the highest average ratings provides valuable insights into the audience's preferences. It will help Microsoft understand which genres tend to receive the highest ratings, aiding in decision-making on film types.
The model, in my case, is a representation of the data analysis approach rather than a predictive model. The fit is determined by how well the code accurately calculates and visualizes the top genres based on average ratings.

## Correlation Between Weighted Average Rating and Domestic Gross:
The scatter plot illustrating the correlation between the weighted average rating and domestic gross allows Microsoft to explore potential relationships between audience ratings and financial success. This insight is crucial for making strategic decisions on film production. The fit of the scatter plot is determined by how well it represents the correlation between weighted average ratings and domestic gross based on the available data.

## Generalization and Business Impact:
The dataset is a good representation of potential future scenarios, the insights gained from the analysis may be applicable to similar situations.For the potential business impact because the top genres are in alignment with audience preferences, Microsoft can make informed decisions on film production and potentially maximize on success.

## Benefits to Business
The model, in this context, is a tool for exploratory data analysis. Its benefit to the business lies in providing actionable insights and informing strategic decision-making for Microsoft's entry into the entertainment industry.

## Conclusion
Top 10 Genres by Average Rating:
The bar plot successfully identifies the top genres with the highest average ratings, providing insights into audience preferences.
This information can guide Microsoft in making strategic decisions about the types of films to prioritize.

Correlation Between Weighted Average Rating and Domestic Gross:
The scatter plot explores the relationship between weighted average ratings and domestic gross, aiding in understanding the potential financial success of films.

Limitations:
The analysis is limited by the representativeness of the dataset. If the dataset does not adequately capture the diversity of audience preferences, the recommendations may be skewed.

## Recommendations
Utilize insights from the top genres by average rating to strategically select film genres that align with audience preferences.
Consider the correlation between weighted average rating and domestic gross to strike a balance between creating artistically valuable films and ensuring commercial success.
To enhance confidence in the results, continuous validation, refinement, and consideration of external factors influencing the entertainment industry are essential. 

## Reasons why my analysis might not fully solve the business problem?

There is a limited data scope. The analysis I have done is based on available data, which may not cover all relevant factors influencing film success. A more extensive dataset may provide a more comprehensive analysis.

Audience ratings are subjective and may not fully capture the nuanced reasons behind film success. Factors like marketing, competition, and timing are not explicitly considered in this analysis.

