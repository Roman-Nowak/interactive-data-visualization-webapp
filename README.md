# PROJECT DESCRIPTION
![plot](./INTERACTIVE_DATA_VISUALIZATION.png)
* This is a webapp written with dash created as a project for a Usability Engineering & User experience Design class at the Jagiellonian University (within the Cognitive Science department).
* The main purpose is to expose the user to the beauty of data visualization by letting them interact with the visualizations.

# HOW TO USE THIS PROJECT
* You can run it locally by cloning the repo and running the code in jupyter notebook or jupyter lab.
* Make sure you install the dependencies before running the project.
* **You will also have to update the paths in both the jupyter notebooks.**

# CONTENTS
* twitter_webscraping.ipynb
    * Code which scrapes twitter for #LUNA
    * Data exploration
    * Data cleaning
    * Wordcloud plots
* DASH_WEBAPP.ipynb
    * the code which is rendered into the website
    * includes all plots and interactive elements
    * written mainly with dash

## Datasets
* twitter_data is a directory with a file containing 1000 tweets with #LUNA scraped from twitter
    * although after cleaning and filtering the data the resulting dataset contains 457 tweets.

# LIBRARIES
* twitter_scraper_selenium https://github.com/shaikhsajid1111/twitter-scraper-selenium
* langdetect - https://github.com/Mimino666/langdetect
* dash - https://plotly.com/dash/
* plotly - https://plotly.com/
* wordcloud - https://amueller.github.io/word_cloud/
* Pillow - https://pillow.readthedocs.io/en/stable/
* if you want to run this from jupyter notebook or jupyter lab you have to install jupyter-dash https://github.com/plotly/jupyter-dash

# TODO
* enlarge the twitter-#luna dataset
* filter the keywords?
* include storytelling elements - "the data should tell a story"
    * ~~first show the plot of the price movement of LUNA~~
    * ~~then positive/negative keyword frequency on a bar plot~~
    * Then show **Concordance** and **Collocations**
    * ~~then wordclouds~~
    * Display a description of the visualization with each step of the slider
* include more interaction options
    * update the UI
        * Right side - interactive controls
        * Left side - instructions
* create / scrape / find other datasets
* add a better graphical design

# AUTHORS
* Agata Serafin - graphical & content design
* Roman Nowak - implementation