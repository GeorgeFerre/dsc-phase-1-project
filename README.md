![](/photos/small_header.jpg)

# Microsoft's New Movie Studio
#### Authors: Bradly Horn and George Ferre

## Overview

This project uses data from Rotten Tomatoes, TheMovieDB, and The Numbers and analyazes it to come up with three suggestions for helping the head microsoft's new movie studio department. It will aim to answer the following: What genre of films are most profitable basic off the ratio of averge production budget to worldwide gross. It will show team recommendations for writers and directors.

## Business Problem

Microsoft would like to expand their media offerings, and have decided to create a new movie studio. Microsoft would like help getting started. Giving recommendations to the head of Microsoft's new movie studio and help decide what type of films to create that will be most profitable while also being received well by critics.

### Three Recommendations

Types of genres to make basic off averge worldwide gross.

Writers are the ideal to create a great story line that all will want to see.

The best possiable directors to lead the moive to be a smach hit.

## Data Understanding

We will be using data from three different places:

The Movie Database (TMDb), which is a massive community built movie and TV database.

The Numbers, the largest freely available database of movie industry information on the web.

Rotten Tomatoes, one the world’s most trusted recommendation resources for quality entertainment.

## Methods

This project analyzes the average worldwide gross for the different genres that have been made in the last 20 years. We also took a look at the rating vs gross ratio from rotten tomatoes to see if there is a correlation between the two.

![](/photos/Scatter.png)

Unfortunately, there does not appear to be a strong correlation between the two. However, we can still take both into account using a new number that we will call the Gross Profit x Freshness (GxF) ratio. The GxF will be calculated by multiplying the box office numbers with our freshness rating.

## Results

![](/photos/Genre_plot.png)

So base of an averge of worldwide gross for each genre, it looks like are top three genres are animation, adventure, and fantasy just beating over family. Using this information, we can pull the top five writers and directors in each genre. For our purposes here, we will look at the top three: Animation, Adventure, and Fantasy.

![](/photos/writer_plot.png)

We can take the top five prospects based on quality ratio. Looking at our newly created graphs, we can see that there is a bit of a dip in quality ratio after the first one or two prospects. This does not necessarily indicate that the other choices of the top five are bad, but that we want to more aggressively go after the top one or two writers in each category.

![](/photos/director_plot.png)

We see a similar situation when viewing the top five directors based on FxG in each genre. We want to put more effort into reaching out to the top two prospects in each genre.

## Conclusions

Conclusions
So are analysis leads to the following findings:

#### 1. Types of genres to make basic off averge worldwide gross.
Looking at are chart for averge of worldwide gross for each genre, we have animation, adventure, and fantasy as the top 3 highest.

#### 2. Writers are the ideal to create a great story line that all will want to see.
We would like to reach out to the following writers:

Animation: John Logan
Adventure: Neal Purvis
Fantasy: Steve Kloves

#### 3. The best possiable directors to lead the moive to be a smach hit.
We would like to reach out to the following directors:

Animation: Gore Verbinski
Adventure: Sam Mendes
Fantasy: Chris Columbus

## Next Steps

1. Categorize genres into subgenres to get more detailed information on what is trending.

2. Look into movie genre combinations. We began by isolating genres to see what is most popular, but would also like to get information on what combinations do best.

3. Generate recommendations for actors, similar to our process for finding writers and directors.

## For More Information

For more details you can look at our [Jupyter Notebook](https://github.com/GeorgeFerre/dsc-phase-1-project/blob/main/Final%20Tech%20Notebook.ipynb) or [our presentation](https://github.com/GeorgeFerre/dsc-phase-1-project/blob/main/movie_slide_deck.pdf).
