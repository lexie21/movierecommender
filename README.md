# Movie Recommendation Engine

<details>
<summary><b>Check out my other projects!</b></summary>
  
[Demand Forecasting](https://github.com/lexie21/demandforecasting)

[Loan Defaulter](https://github.com/lexie21/loandefaulter)

</details>

## Table of Contents
- [Introduction](#Introduction)
- [EDA](#Exploratory-Data-Analysis)
- [Modeling](#Modeling)

## Introduction

<b>What this project is about?</b>

- Project Scope

  Our objective is to explore how many ratings are given and whether they tend to be high or low, segmented by viewer demographics. By identifying patterns in how different groups rate movies, we can gain insights into audience preferences and biases.

  The findings from this analysis will serve as a foundation for the next stage—developing a personalized movie recommendation system. By understanding rating tendencies across different viewer segments, we can refine recommendation algorithms to provide more relevant and engaging movie suggestions.

<b>What I did?</b>

- EDA
  
  Explored rating distributions and trends across different viewer demographics to understand audience preferences.

- Recommendation Engine
  
  Used popularity-based recommendations as a starting baseline, followed by user-based approach, matrix factorization via SVD and finally neural collaborative filtering for more personalized recommendations


## Exploratory Data Analysis

<h3>Metrics and Dimensions</h3>

- **Rating count:** measures how popular a movie is and how engaged/active the viewers on our platform are.
- **Average rating:** indicates how positive our movie selection is perceived. 

<h3>Summary of Insights</h3>

<h4>Metrics through Time</h4>

![Alt Text](https://github.com/lexie21/movierecommender/blob/main/ratings.png)

<h4>Rating Count by User and Movie:</h4>

![Alt Text](https://github.com/lexie21/movierecommender/blob/main/frequency.png)

<h4>User Statistics:</h4>

![Alt Text](https://github.com/lexie21/movierecommender/blob/main/user_stats.png)

<h4>Movie Statistics:</h4>

![Alt Text](https://github.com/lexie21/movierecommender/blob/main/movie_stats.png)




## Modeling
![Alt Text](https://github.com/lexie21/movierecommender/blob/main/MF.png)
![Alt Text](https://github.com/lexie21/movierecommender/blob/main/metrics.png)
