# group_4_project

View the interactive story here: https://public.tableau.com/shared/NSFGDHH6K?:display_count=n&:origin=viz_share_link
## Overview
This company has decided to take up a new challenge, and that is the film industry — and this is what this notebook aims to do. In this notebook is a comprehensive analysis of the top movies across time to get a better sense of what they are getting into.
## Business Problem
As they venture into the film industry, they need a top-down analysis of the most successful titles to understand where and how to channel their resources effectively. The goal is to produce impactful films that resonate with audiences and stand the test of time. This analysis will help identify what types of films are currently performing best at the box office and provide actionable insights to guide the decisions of the new movie studio.
## Data
There is an abundance of data sources that are in the publc domain in which we can use in this analysis but in this analysis we will use datasets from IMDB and Box Office Mojo specifically:

 . imdb.title.basics
 . imdb.title.ratings
 . bom.movie_gross
 . tn.movie_budget.tsv
 ## Methods and Exploration
 For an indepth analysis of the dataset, the cleaning and analsysis of the datasets was done in a separate notebook movie_analysis.ipynb as to not make this one long.

In order to explore the data i sought out to find questions that resonate with the bussiness problem at habd and they were:

Most successful film studios in the industry
Most successful genres in the industry
Trends in genres over the years
Typical Runtime of a succesful film
We used two key methods of analysis on the dataset above:

Statistical analysis: For certain questions like succesful studios and typical runtime i sought out to use covariance to see what is the success rate of a studio in regards to the number of films produced and median to see the typical runtime of a successful film

Visual analysis: All questions have some form of visualization that is to answer the respective question

<img width="1590" height="1190" alt="image" src="https://github.com/user-attachments/assets/6c8855b0-5473-4bcd-860f-a69869468875" />


## Results
The results are based on the four questions above:

In this i decided to sample the top 20 genre categories and use 3 of them in here:


Average Ratings: The top genres include
1. Animation
2. Sci-Fi
3. Adventue
4. mystery
5. Comedy
6. Romance
7. Fantasy
8. Action
9. Biography
10. Family

<img width="1187" height="589" alt="image" src="https://github.com/user-attachments/assets/bce8d7c6-efce-4d8b-bf2c-4abad00c5742" />


4. Runtime of a successful Film

The median of a typical succesful film is:

Median Rating: 7.3

Median Runtime: 104.0

Median Gross: 1076004500.0

<img width="1790" height="590" alt="image" src="https://github.com/user-attachments/assets/320c08f9-e4ca-46de-a461-651dffc5b201" />


## Conclusions
From the results obtained, it is safe to reccomend:

. For the specific category, i highly recomend starting out with a mix the following as they are the most prommising:
1. Animation
2. Sci-Fi
3. Adventure
4. Mystery
5. Comedy
6. Romance
7. Action
. For Runtime of a succesful film they should try and keep their runtime in the range of 120 - 130 minutes

. For a relevant genre they should focus on Adventure, Action, Sci-Fi

Final Recomendation: The data itself testifies that the most promissing places to start is Animation.



