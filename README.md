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
 For an indepth analysis of the dataset, the cleaning and analsysis of the datasets was done in a separate notebook eda/exploration.ipynb as to not make this one long.

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
1. Successful studios
Notebook_visuals/film studio performance.png
The above is a figure containing 4 scatter plots divided into two groups and two sub groups:

Total Gross: In this we can see an almost identical correlation between the gross value of a film studio and the number of fils that studio has given out. (Domestic Gross: 0.73, Foreign Gross: 0.72) this suggests that the two have a strong assosiation

Average Gross: In this, they are almost similar but here rather they have a week correlation coeficient (Domestic Gross: 0.14, Foreign Gross: 0.10)
2. Popular Genres

In this i decided to sample the top 20 genre categories and use 3 of them in here:

The above visualisation contains three plots:

Average Ratings: The top genres include
1. Adventure, Drama, sci-fi
2. Action, Comedy, Fantacy
3. Mystery, sci-fi, thriller
Average Votes: (this is where most film heads are)
1. Adventure, Drama, sci-fi
2. Adventure, mystery, sci-fi
3. Action, Adventure, sci-fi
Total Gross
1. Action, Adventure, sci-fi
2. Action, Adventure, fantacy
3. Action, Adventure, Thriller
4. 
<img width="1187" height="589" alt="image" src="https://github.com/user-attachments/assets/bce8d7c6-efce-4d8b-bf2c-4abad00c5742" />

3. Trends Over Time

From the above visualisation we can see that Adventure, Animation, Comedy and Action, Adventure, sci-fi have been leading consistently over the span of nine years in terms of gross

4. Runtime of a successful Film

The median of a typical succesful film is:

Median Rating: 7.3

Median Runtime: 126.0

Median Gross: 1076004500.0

<img width="1790" height="590" alt="image" src="https://github.com/user-attachments/assets/320c08f9-e4ca-46de-a461-651dffc5b201" />


## Conclusions
From the results obtained, it is safe to reccomend:

. For the specific category, i highly recomend starting out with a mix the following as they are the most prommising:
1. Action
2. Adventure
3. Sci-Fi
4. Drama
5. Fantancy
6. Thriller
. For Runtime of a succesful film they should try and keep their runtime in the range of 120 - 130 minutes

. For a relevant genre they should focus on Adventure, Action, Sci-Fi

Final Recomendation: The data itself testifies that the most promissing places to start is Action Adventure and Sci-Fi.

