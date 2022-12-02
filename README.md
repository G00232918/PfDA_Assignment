# PfDA_Assignment
# Project 1
- Author - James Connolly
- Student_Number - G00232918
- Module - Programming for Data Analysis


#### Problem statement
For this project you must create a data set by simulating a real-world phenomenon of
your choosing. You may pick any phenomenon you wish – you might pick one that is
of interest to you in your personal or professional life. Then, rather than collect data
related to the phenomenon, you should model and synthesise such data using Python.
We suggest you use the numpy.random package for this purpose.
Specifically, in this project you should:
- Choose a real-world phenomenon that can be measured and for which you could
collect at least one-hundred data points across at least four different variables.
- Investigate the types of variables involved, their likely distributions, and their
relationships with each other.
- Synthesise/simulate a data set as closely matching their properties as possible.
- Detail your research and implement the simulation in a Jupyter notebook – the
data set itself can simply be displayed in an output cell within the notebook.

#### Table of Contents

#### Sources -
https://www.youtube.com/watch?v=YREIn1uTYO0 - How to create a Table of contents in Jupyter notebook.

* Introduction 
I give an introduction as why I have chosen this dataset.

###  2. Variables used in dataset

#### Sources -
- https://www.irishmirror.ie/sport/other-sport/snooker/stephen-hendry-snooker-uk-championship-28375687 - Reference from a top amateur on how many hours he practices. 
- https://www.eurosport.com/snooker/mark-selby-questions_sto2126796/story.shtml - How I found the amount time a world champion practices. 
- https://docs.google.com/spreadsheets/u/1/d/e/2PACX-1vReSa_maD9dB-HoAgnMCCNLQwSAH9IARqjDoxjcBrqfwy3KWI6Am46xN2Uolc6dnnLEkGKQhtUAkZ7F/pubhtml - Last senior ranking table in Ireland to base number of wins off.
- https://cuetracker.net/statistics/matches-and-frames/won/season/2020-2021?status=professional&categories=ranking,minor-ranking,non-ranking,league,invitational,tour-qualifier,6-reds - Check how many wins stayed on the tour last season, based off the last player on the list and adding the wins needed to get on tour.
- https://snookerinfo.webs.com/100centuries - Century table.
- https://www.dailymail.co.uk/sport/othersports/article-3063040/
- It-played-60million-China-World-Championship-comes-climax-Snooker-gone-pot.html - I weighted the centuries column based on this article.

### 3. Setting up dataframe -
Imports being used are defined in the beginning. Then the number of players are defined based on requirement of the project. 

The rest of the code is commented to mention what is the purpose. 

#### Sources -

- https://www.geeksforgeeks.org/create-a-dataframe-from-a-numpy-array-and-specify-the-index-column-and-column-headers/?ref=lbp - Examples on how to set a dataframe correctly.
- https://stackoverflow.com/questions/36667548/how-to-create-a-series-of-numbers-using-pandas-in-python - Reference for creating range for player column.
- https://numpy.org/doc/stable/reference/random/generated/numpy.random.choice.html - Reference for gender column to set probability.
- Lecture notes - random commands.
- https://www.dataquest.io/blog/tutorial-add-column-pandas-dataframe-based-on-if-else-condition/ - Reference code for creating status column.

### 4. Data Analysis

### 4.1 Review of data
- df.head
- df.types
- df.value_counts(status)
- pd.unique(df['status']) 

#### Sources -
- Lecture notes.
- https://pandas.pydata.org/docs/reference/api/pandas.unique.html

#### 4.2 Show the status count

#### Source -
https://seaborn.pydata.org/generated/seaborn.countplot.html

#### 4.3 Show the disparity between Male and Female players
- Plotting the status count in graph with seaborn.

#### Source -
https://seaborn.pydata.org/generated/seaborn.countplot.html

#### 4.4 Century Class vs Practice
- Measuring Century class against the amount of practice hours a player is doing.

#### Source -
- https://seaborn.pydata.org/generated/seaborn.boxplot.html

#### 4.5 Scatter plot for status vs wins
#### 4.6 Scatter plot for status vs practice

#### Source -
- https://www.w3schools.com/python/matplotlib_scatter.asp

#### 4.7 Heatmap 
### Source -
- https://seaborn.pydata.org/generated/seaborn.heatmap.html

### 5. Normal Distribution for competitive wins
### Source - 
https://stackoverflow.com/questions/71287607/how-to-make-a-normal-distribution-graph-from-data-frame-in-python - Code for normal distribution

### 6. Conclusion
- Final thoughts on the project.

