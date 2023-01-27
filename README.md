# Exploring Movie Data to Provide Business Recommendations

<img src="nicole-kidman-nicole.gif" width="750" align="center">


## Overview 
### Hollywood is highly saturated. How would a newcomer make movies that make money?

The brief: Microsoft sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t know anything about creating movies. 

Explore the data to determine what types of films are currently doing the best at the box office. Translate these findings into actionable insights a company like Microsoft can use.


## The Data

Movie information, including titles, runtime in minutes, and genres were collected from __[IMDB](https://www.imdb.com/)__. 

Additionally, I used data from __[The Numbers](https://www.the-numbers.com/)__ that included release dates for movies, production budget, domestic gross revenue, and worldwide gross revenue.


## Data Understanding

The major determinant for a successful movie is profit, both worldwide profit and domestic. Worldwide and domestic profit are determined by subtracting production budget from worldwide gross revenue and domestic gross revenue respectively. 

Data cleaning included removing all values that did not include gross revenue information as profitability is key. Then analysis used descriptive analysis and visualization to determine the most profitable months of release, top-earning genres, typical runtimes for those genres, and directors with highest ROI on production budget.


## Findings


<img src="Images/Profits by Month.png" width="750" align="center">

 - Worldwide release profits are considerably higher than movies that are just released domestically.
 - The best months for movie releases are May, June, July, November, or December. September is the worst month for a movie release.

<img src="Images/Profits by Genre.png" width="750" align="center">

 - Animation, Musical, Sci-Fi, Adventure, and Action films are the most profitable genres (in that order). 
 
<img src="Images/Runtime by Genre.png" width="750" align="center">

 - For the most profitable genres, runtime should be between 92-107 minutes. 
 - Action and Adventure films are typically around 95 minutes, Fantasy around 98-101 minutes, Musicals around 104 minutes, and Sci-Fi around 92 or 107 minutes.
 
 <img src="Images/Top Director ROI Genre.png" width="750" align="center">

 - Chris Lofing or Travis Cluff, horror co-directors at Tremendum Pictures, have the highest ROI when looking at production budget and worldwide gross revenue.
 

## Recommendations

In summary, the data shows Microsoft should do the following to maximize profits:

 - __Focus on worldwide releases.__
 - __Release movies in May, June, July, November, and December. DO NOT release in September.__
 - __Release action, adventure, animation, musical, and/or sci-fi films.__
 - __Animation films are typically either 89 or 95 minutes. Action, and Adventure films are typically around 95 minutes, Musicals around 104 minutes, and Sci-Fi around 92 or 107 minutes.__
 - __Hire Chris Lofing and/or Travis Cluff to direct.__
 

## Next Steps

1. __Update the data with more recent information.__ The vast majority of the data we used is from 2019 or before. Recently successful films are better indicators of future successful films. The pandemic as well majorly influenced cinema-attendance trends with a move towards home streaming for new releases. To continue making recommendations, we need to understand how people are watching movies now.

2. __Consider marketing and branding.__ Some of the most successful films in our dataset come from movie franchises like Fast & Furious, major brands like Marvel and Disney, and have highly expansive digital and media advertising strategy attached. It's worth looking at how advertising and brand recognition come together to determine profitability.

3. __Determine the brand niche.__ While a lot of the analysis above is centered around maximizing profits, it's clear to see that the current marketplace for movies is overcrowded with superhero films, high-budget CGI productions, and movies that generally require high investment for high reward. It is worth it to consider whether a brand like Microsoft can make a niche in one genre, like Horror, Thriller, or Video Game Adaptations, or via a medium like streaming, or within a smaller production budget range.
