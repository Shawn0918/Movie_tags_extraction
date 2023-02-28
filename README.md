## Blog site
<https://shawn0918.quarto.pub/movie-tags-extraction-blog/posts/2022-08-31-final_project.html>

### Interact with my project with Binder!
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Shawn0918/Final_Project/HEAD)

## Introduction

This project is a preliminary attempt to create tags for categories of movies found on Netflix based on information in the *Netflix Movies and TV Shows* dataset. 

## Motivation 

As a movie fan, I’m always strict about selecting a movie for my scarce holidays. Instead of blindly choosing a blockbuster movie, I prefer to scrutinize the movie recommendation websites to choose a movie that might not be popular, but perfectly fits my desire. In the process of looking for movies, I find my focus usually falls on two sites——the tags attached to the movie and the comments from the viewers. It seems like sometimes apart from the category the movie is classified in, such as comedies, or romantic movies, the elements that appear in a movie are more helpful for my search. For instance, if the name “suspension film” appears on the recommendation page, I probably wouldn’t pay any attention to it, while if the tag “psychopathic killer” is added, I would be very likely to click in to see if that’s my target film. The accurate tags on the films can not only benefit the viewers, but they can also help improve the performance of recommendation systems and thus can indirectly boosts their profit. Considering that most movie fans are not selecting films simply based on the rough categories, or the genres, it might be more appropriate to push the films on the basis of the tags on the movies they’ve recently seen. Furthermore, such a tag-attaching system also helps those movies with less popularity but with highlighted characteristics to gain more viewers, which could facilitate the diversification of the movie industry. 

## Previous Literature

Movies tagging has been researched extensively with natural language processing and machine learning methods. In a study by Khan et al.(2017), they trained a Convolution Neural Network based on a carefully constructed tag vocabulary to extract the keywords from the keyframes in the movie, and achieved good accuracy in their evaluation. In a study conducted by Kar et al.(2018), researchers came up with a model which can extract tags on the basis of a paragraph of synopses about the movie. The researchers found an obvious superiority in the relevance and attractiveness of the model’s outcome over the keywords extracted by humans. Moreover, they put forwards a list of requirements for the synopses used for tag-extraction. The result of this study demonstrates the feasibility of generating tags with a synopsis of the movie. 


## Datasets used

This study will mainly use the dataset “Netflix Movies and TV Shows” by Shivam Bansal. The dataset contains the basic information about movies on Netflix, including information such as the movie types, descriptions and directors that are useful in building the connection between directors and types of movies. 


## Research Scope

First, the study chooses the top 10 famous directors from the website https://www.imdb.com/list/ls056848274/ and applies type-specified analysis to the movies they directed. This study uses the main dataset to extract the keywords from movie descriptions to analyze directors’ preferences for different types of movies. Then the research generates a preliminary report for those famous directors, including visualizations such as a histogram to indicate the number of different types of movies they’ve directed. Then the study applies some methods used in Natural language processing(Nlp) to analyze the comments on those films on TMDb, to capture similar impressions after watching one director’s film. Besides, sentiment analysis is also included to implement the preliminary classification of the comment. 

## Result & Conclusion

In this project, the keywords are successfully extracted from a list of movie descriptions by the LDA model and get visualized through several wordcloud graphs, which proves the feasibility of extracting the featured words from a set of short sentences.
