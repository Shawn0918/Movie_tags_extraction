## Introduction

The quality of a movie is largely decided by its director. An extraordinary director can produce a fantastic movie out of an ordinary story. As renowned movie directors usually follow their styles of directing movies, which might form during decades of directing, It’s common for a movie fan to establish an overall impression of all the movies directed by his favorite director. A classic case to show the personal directing styles might be the comparison between the different versions of Batman, which have been successively directed by Tim Burton, Christopher Nolan and Matt Reeves. Some of those versions underscore Batman’s heroic spirit, some pay more effort to discussing the good and evil in society, and some raise the question about Batman’s unjustified power of administrating the order of society. Moreover, a director’s style of making a movie might fall on a particular movie type. For instance, if you’re a fan of suspense movies you must’ve heard of David Fincher, or if you have an interest in imagining the unknown, you shouldn’t miss Christopher Nolan. The amazing connection between directors and movie types is of great research interest, and applying the methods in data science is undoubtedly the optimal solution for this research. 

## Research Value

In my spare time, watching a movie is one of the best ways to relieve pressure. Once I found some similarities between different movies of a director, such a similarity in either the holistic style or some details, it made me search for a movie of interest more quickly, and thus freed me from lingering on the recommendation page and searching for each of them on IMDb. Such research on directors and their movies might give some new inspiration to the movie recommendation system. From the perspective of audiences, this study gives them an overall impression of movie directors, enabling them to quickly pick up a movie and have a better watching experience.

## Datasets used

This study will mainly use the dataset “Netflix Movies and TV Shows” by Shivam Bansal. The dataset contains the basic information about movies on Netflix, including information such as the movie types, descriptions and directors that are useful in building the connection between directors and types of movies. 
Apart from that, this study might also involve the dataset “TMDB 5000 Movie Dataset” by The Movie Database (TMDB), which contains users’ comments on movies. 

## Research Scope

First, the study chooses the top 10 famous directors from the website https://www.imdb.com/list/ls056848274/ and applies type-specified analysis to the movies they directed. This study uses the main dataset to extract the keywords from movie descriptions to analyze directors’ preferences for different types of movies. Then the research generates a preliminary report for those famous directors, including visualizations such as a histogram to indicate the number of different types of movies they’ve directed. Then the study applies some methods used in Natural language processing(Nlp) to analyze the comments on those films on TMDb, to capture similar impressions after watching one director’s film. Besides, sentiment analysis is also included to implement the preliminary classification of the comment. 

## Expected Conclusion

To form some director-specified sections of movies, such as Nolan’s sci-fi movie and Quentin Tarantino’s crime films, which contains their profiles, an introduction to their movie styles, and some of their repres
