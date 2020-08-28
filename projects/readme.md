# Machine Learning Projects


## General Instructions
Projects allow you to explore a dataset and experiment with the techniques covered in the labs--can you apply what you learned on a new dataset? 
For all projects you are to create a Jupyter Notebook containing both your code and your commentary. 

The commentary is more than just comments on the code. When I normally code, I only comment what is unclear, meaning I would never have comments like:

```
# import the pandas library
import pandas as pd
# read in the data file
bach = pd.read_csv('../data/bach.csv')
# get the list of columns
columns = list(bach.columns)
```
and probably would comment something like

```
# convert the categorical columns to boolean
for note in notes:
    bach[note] =  bach[note].apply(lambda x: True if x == 'YES' else False)
bach
```

However, for these project commentaries I want the redundancy shown above. Say what you are doing in markdown then do it in code. I think this is a good pedagogical approach and will help you step logically through a problem.

A good starting point for what a notebook could look like is Nadin Tamer's notebook [Titanic Survivor Predictions (beginner)](https://www.kaggle.com/nadintamer/titanic-survival-predictions-beginner). She even gives a nice outline explaining the steps she will take. 

Notice that part of her notebook involves looking at the data. This is a crucial step. Are there missing values? Are there categorical columns that need to be one-hot encoded? The thought processes in your head should be recorded in the markdown sections of the notebook. 

Once you do all this preprocessing, you may want to just build a basic classifier and get an initial accuracy measure on the test set. This just verifies that the data format is good and gives you a baseline accuracy before you start investigating ways of making improvements. Your work does not stop when you make the first classifier.

Projects are intentionally vague. I want you to engage your brain and not simply convert a set of instructions I write, to code. Again, this is your chance to explore a dataset and experiment with techniques from the labs.

#### Submitting your code

You should save your completed Python notebook to your github repository and notify me by [filling our this form](https://forms.gle/biRtucrbnKaGTfAe6)

## 


| Order | Lesson                                         |
| ----: | :--------------------------------------------- |
|     1 | [Bach Chorales](Bach.md)                           |
|     2 | [TBD](pandas.ipynb)                         |
|     3 | [TBD](intro-to-sklearn.ipynb) |






