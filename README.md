# Action! An Exploratory Data Analysis on Film Production

What are the best films to be produced by Return-On-Investment and profits? An exploratory data analysis on film production in the last 5 years, from 2014 to 2019, using scraped data from IMDBPro. A project developed for Module 1 of the Online Data Science Bootcamp at Flatiron School.

Mini-website: https://readymag.com/kosmonauts/action-eda/

## Project Outline


## Recommendations
Our guiding question throughout our analysis has been:
    - What type of films are currently doing the best?

In the context of Microsoft willing to open a movie studio, this question could be translated as:
    - In what type of films Microsoft should invest?

In terms of investment, initial budget, profits and Return-Of-Investment (ROI) are keys. 
We then moved to our analysis to:

    - What are the most intersting genres in terms of ROI?

To do so, we used two models:
- **Model 1**: we  categorized films by two genres. This approach does give more precise information on what specific subgenre is more promising. However, due to lack of data, it becomes unreliable when it comes to make recommendations on other essential aspects of the film business: who to involve to "make it" - producers, directors, writers and actors. For this reason, we used model 2 when it came to make recommedations on who to select for our future cast.

- **Model 2**: we categorised films by their main genre. The trade off with respect to Model 1 was to lose some granularity in terms of the specific, potentially most profitable subgenres. Neverthless, first we spotted the main potential genres in terms of ROI. Then we analysed their trends througout the years. We want to produce films that belong to "trending" genres not to those who show signs of decline. 


From the data we learnt that:

/Users/marco_nasuto/Desktop/profits-budget.png
    - High profits require high budget

/Users/marco_nasuto/Desktop/roi-budget.png
    - ROI and budget are not related

We spotted three main genres where to start producing films by ROI: 

/Users/marco_nasuto/Desktop/profits-per-genres.png

/Users/marco_nasuto/Desktop/roi by genres .png

    - Action
/Users/marco_nasuto/Desktop/roi action years.png
    - Adventure
/Users/marco_nasuto/Desktop/roi adventure years.png
    - Animation
/Users/marco_nasuto/Desktop/roi animation years.png

  We also see potential in two more genres that have been growing in the last 5 years
    - Comedy
/Users/marco_nasuto/Desktop/roi comedy years.png
    - Horror
/Users/marco_nasuto/Desktop/roi horror years.png

Whereas it is possible to come up with recommendations on potential sets of cast to hire for Action, Adventure, Animation and Comedy films, there is not enough data for Horror films.

## Example of  a film to produce

- Genre: **Action** - highest profits, high median ROI
- Producers: **Kevin Feidge** - high median ROI, a significant number of films in the last 5 years (3 films produced)
- Directors: **Anthony Russo** - high median ROI, high number of films in the last 5 years
- Writers: **Stephen McFeely** - good median ROI, high median profit
- Actors: **Chris Evans, Robert Downey Jr., Don Cheadle** - high median ROI, high profits, high number of films in the last 5 years