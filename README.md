# Project Three: A short Berlin Club History

For the third Project of the Lede Program 2024 I looked into the history of Clubs in Berlin. 

## Project Idea

In this third project I wanted to do some mapping and because I recently did a piece on the rich history of Clubs in Berlin, I decided to make it into a map story.
I wanted to show three time periods in my piece: the beginning of the modern club scene in east and west Berlin, the rise of techno in the years after the fall of the Berlin Wall and the recent developements and challenges the clubs face today.

## Data

There are many clubs in Berlin, some world-famous, some really small. It was quite hard to find a complete dataset for all clubs currently open in Berlin, in part because there is not really a clear definition of what constitutes a club. In the end, I got my data from the [tourism portal of the City](https://www.visitberlin.de/de) as they had complete date as well as a well structured website, which made it easy to scrape.

Getting the data for my historical maps prooved to be quite hard: There were many websites with incomplete datasets. The best datasets I could find were from an [App made with the Berlim Clubcommission](https://www.clubcommission.de/verschwundene-orte-der-berliner-clubkultur/), an alliance of clubownwers in Berlin. I did not know how to scrape an app so I used screenshots to extract the data and had to research for addresses myself.

After I had all my data, I geocoded it with the Google Geocoding API.

Clubs in Berlin:
* [This](https://github.com/ljmirani/berlin-clubhistory/blob/main/scrape_Clubs.ipynb) Notebook has the code I used to scrape the data from the Berlin tourism website
* [This](https://github.com/ljmirani/berlin-clubhistory/blob/main/geocode_clubs.ipynb) Notebook has the code I used to geocode the data


Clubs in East and West Berlin:
* [This](https://github.com/ljmirani/berlin-clubhistory/blob/main/scrape_EastWest_Screenshot%20copy.ipynb) Notebook has the code I used to extract the data from the screenshots
* [This](https://github.com/ljmirani/berlin-clubhistory/blob/main/geocode_clubs_eastwest.ipynb) Notebook has the code I used to geocode the data

Closed Clubs:
* [This](https://github.com/ljmirani/berlin-clubhistory/blob/main/scrape_ClosedClubs_Screenshot.ipynb) Notebook has the code I used to extract the data from the screenshots
* [This](https://github.com/ljmirani/berlin-clubhistory/blob/main/geocode_closed_clubs.ipynb) Notebook has the code I used to geocode the data

## Maps

I made my maps using Datawrapper and Illustrator. With ai2html and scrollama I made my project into a scrollytelling piece.

## Website

[This](https://ljmirani.github.io/berlin-clubhistory/) is the website that I created for this project.

## What I learned
* Making Maps
* Finding different/creative ways to get to my data
* Basics of Scrollytelling/using scrollama


## What I would have liked to do (with more time/skills)
* I am not very happy with the overall design: I wanted to make my maps wider, but could not figure out how.
* I also wanted to make a few charts to go with the mapping stories, but ran out of time.
* I wanted to improve upon my dataset and maybe figure out a different way to get to my data
* Many tiny improvements/details in the story (titles for the maps, zooming etc.)


## Contact

Jaya Mirani, [j.mirani@proton.me](mailto:j.mirani@proton.me)
