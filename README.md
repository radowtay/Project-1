# Project_1

![IMDB_Logo](1200px-IMDB_Logo_2016.svg.png)


## Group: Wanna Fight About It? 

## Table of content
* [General info](#general-info)
* [Questions](#questions)
* [Data Sources](#Data-Sources)
    * [Preview](#preview)
* [Data Cleaning](#Data_Cleaning)
* [Setup](#Methods-Used)
* [Team](#team)

Data Visualization

# Name of notebooks / folders containing different types of visualizations. 

# import actual visualizations 
# with sentances explaining each one. 
=======
#### Project Status: [Active]

## General info
Project Proposal: The purpose of this project is to find out What Factors, if any, produce a successful movie?

## Team
<table>
  <th>Name</th>
  <th>Title</th>
  <tr>
   <td>Rachel Dowdy</td>
    <td>Repository Manager</td>
  </tr>
   <tr>
    <td>Annette Heredia</td>
    <td>Programmer Analyst</td>
  </tr>
  <tr>
    <td>Johnathan Fludd</td>
    <td>Programmer Analyst</td>
  </tr>
  <tr>
    <td>Miguel Martinez</td>
    <td>Programmer Analyst</td>
  </tr>
</table>

### Methods Used
* Inferential Statistics
* Data Visualization
* Predictive Modeling
* Search function via User Input
* etc.


### Technologies
* Python
* Pandas, jupyter
* Matplotlib
* APIs
* etc. 

## Data Sources

IMDB 5000 Movie Data
https://www.kaggle.com/carolzhangdc/imdb-5000-movie-dataset


## Data Cleaning

movie_meatadata.csv was our original file. 
Cleaning Movie Data is our cleaned file. 
We removed columns that were not relevant or had little to no data. 
We Renamed the columns and reordered them to make them have a more intuitive presentation. 
We dropped any rows that had no values. 

## Questions

* What movie(s) rank highest in score with the lowest budget(s)?
   * We put them in to a range of highest rated, mid rated and lowest rated based on IMDB score. We found that " Nothing But a Man" ranked the highest for the high range with a budget of $ 160,000. "Tarnation"ranked highest in thr mid range with a budget of $218. "The Gallows" ranked highest in the low range with a budget of $100,000.

* Busiest Directors - most movies output in a single year
    * For this question, we found that the most movies any director had output in a single year (within the dataset) was two movies.  So, we compiled a visualization of each director that had released two in one year from 1990-2014.  Renny Harlin started the trend, but Clint Eastwood and Steven Spielberg both did it at least four different years.


* Busiest Actors - most movies output in a single year
   * For this question, we found that the most busiest Actor to had ouput in a single year was Denzel Washington. Johnny Depp started first but Denzel Washington and Matt Damon started to get ahead in the movie gain.

* Top 5 Genres in List vs IMDB Rating
   * We Discovered that the top 5 rated Genres based on IMDB rating were: Film-Noir, Biography, History, War and Documentaries. However we also looked into the most and least recurring genres. We deciphered from our analysis that 60% of the Least recurring genres ranked in the top 5 IMDB rated Genres

* Genres with the highest and lowest average budgets
    * We discovered that animated films have the highest average budgets!  This makes sense when one considers the amount of people and work involved in creating large-scale animation.  Within the seven genres with the lowest budgets, Romance was the highest, with Film Noir coming in dead last.


* What countries are represented in the movie dataset, and how often?
    * The first visualization to come from this was incomprehensible, due to the enormous lead the USA had in the dataset.  After we removed the US, we found the same problem with the UK.  Removing both the USA and the UK, we were left with a much more readable visualization that showed films from far lesser represented countries.  France was the lead after the USA and UK.  Finally, to represent the least-represented, we created a pie chart showing all the countries that only released one film within the dataset.




## Project Description
>>>>>>> 32375b987d59c89f38c81696df4d45c06c905fd6
