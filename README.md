# data_analysis
data_analysis

## Version 1.0.0

### Features 1.0.0
- [X]Find and download the following data sets:
 - [X]Video Game Sales - Sales data from more than 16,500 games
 - [X]Cycle Share Dataset - Bicycle Trip Data from Seattle’s Cycle Share System
- [X]Start two Jupyter Notebooks called vg-stats and bike-stats
- [ ]Add a markdown cell at the top of each notebook with the title of this assignment, an appropriate name for the data set, as well as your name and the date
- [ ]Load up each of these data sets into a Pandas DataFrame within each respective file.
 - NOTE: There’s an issue with one of the CSV files. You will need to find a way to handle that error… Google it, and work around it!
- [ ]In the vg-stats notebook answer the following questions/do the following tasks. Note that the numbers quoted for sales are in the millions, and apply only for those games with over 100,000 sales.:
  - [ ]Which company is the most common video game publisher?
  - [ ]What’s the most common platform?
  - [ ]What about the most common genre?
  - [ ]What are the top 20 highest grossing games?
  - [ ]For North American video game sales, what’s the median?
    - [ ]Provide a secondary output showing ‘about’ ten games surrounding the median sales output
  - [ ]For the top-selling game of all time, how many standard deviations above/below the mean are its sales for North America?
  - [ ]The Nintendo Wii seems to have outdone itself with games. How does its average number of sales compare with all of the other platforms?
  - [ ]Come up with 3 more questions that can be answered with this data set.
- [ ]In the bike-stats notebook, answer the following questions/do the following tasks:
  - [ ]What is the average trip duration for a borrowed bicycle?
  - [ ]What’s the most common age of a bicycle-sharer?
  - [ ]Given all the weather data here, find the average precipitation per month, and the median precipitation.
  - [ ]What’s the average number of bikes at a given bike station?
  - [ ]When a bike station is modified, is it more likely that it’ll lose bikes or gain bikes? How do you know?
  - [ ]Come up with 3 more questions that can be answered with this data set.
- [ ]When you’re done answering all of the questions for each data set, clean up your notebooks leaving only cells that contain relevant data and calculations. Then restart and run your notebook so that the cell numbering is sequential from top to bottom

- [ ]Have fun with the data!! Play around a bit, and see if there’s anything else you can/want to do with the info available!


## Software Setup
```
pipenv --three
pipenv shell
pipenv install jupyter
jupyter-notebook
pipenv install numpy
pipenv install pandas
```

## Change Log

### 2018-08-30
- Setup scafolding
- installed jupyter notebook
- installed numpy
- install pandas
- Created vg-status and bike-stats