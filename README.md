# PfDA_Assignment
* Introduction 
I give an introduction as why I have chosen this dataset.

###  Variables I have picked are explained.

#### Sources -
- https://www.irishmirror.ie/sport/other-sport/snooker/stephen-hendry-snooker-uk-championship-28375687 - Reference from a top amateur on how many hours he practices. 
- https://www.eurosport.com/snooker/mark-selby-questions_sto2126796/story.shtml - How I found the amount time a world champion practices. 
- https://docs.google.com/spreadsheets/u/1/d/e/2PACX-1vReSa_maD9dB-HoAgnMCCNLQwSAH9IARqjDoxjcBrqfwy3KWI6Am46xN2Uolc6dnnLEkGKQhtUAkZ7F/pubhtml - Last senior ranking table in Ireland to base number of wins off.
- https://cuetracker.net/statistics/matches-and-frames/won/season/2021-2022?status=professional&categories=ranking,minor-ranking,non-ranking,league,invitational,tour-qualifier,6-reds - Main tour matches won from 2021/22 season.
- https://cuetracker.net/statistics/matches-and-frames/won/season/2020-2021?status=professional&categories=ranking,minor-ranking,non-ranking,league,invitational,tour-qualifier,6-reds - Check how many wins stayed on the tour last season, based off the last player on the list and adding the wins needed to get on tour.
- https://snookerinfo.webs.com/100centuries - Century table.
- https://www.dailymail.co.uk/sport/othersports/article-3063040/
It-played-60million-China-World-Championship-comes-climax-Snooker-gone-pot.html - I weighted the centuries column based on this article.

### Setting up dataframe -
Imports being used are defined in the beginning. Then the number of players are defined based on requirement of the project. 

The rest of the code is commented to mention what is the purpose. 

#### Sources 

- https://www.geeksforgeeks.org/create-a-dataframe-from-a-numpy-array-and-specify-the-index-column-and-column-headers/?ref=lbp - Examples on how to set a dataframe correctly.
- https://stackoverflow.com/questions/36667548/how-to-create-a-series-of-numbers-using-pandas-in-python - Reference for creating range for player column.
- https://numpy.org/doc/stable/reference/random/generated/numpy.random.choice.html - Reference for gender column to set probability.
- Lecture notes - random commands.
- https://www.dataquest.io/blog/tutorial-add-column-pandas-dataframe-based-on-if-else-condition/ - Reference code for creating status column.

#### Dataframe requests
- df.head
- df.types
- df.value_counts(status)
- pd.unique(df['status']) 

#### Sources
- Lecture notes.
- https://pandas.pydata.org/docs/reference/api/pandas.unique.html

#### Show the status and Gender 
- Plotting the status count in graph with seaborn.

#### Source
https://seaborn.pydata.org/generated/seaborn.countplot.html

#### Century Class vs Practice
