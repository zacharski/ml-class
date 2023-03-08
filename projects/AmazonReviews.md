# Amazon Musical Instrument Reviews

### [General Readme on Projects](https://github.com/zacharski/ml-class/blob/master/projects/readme.md)



Web commerce sites get a substantial amount of feedback from reviews users post on various websites.  It is not practical to go through all this information by hand to determine whether a user liked a particular product or not. 

For our project we are going to use a dataset of Amazon Musical Instrument Reviews. The main reason I selected this dataset is that it is significantly smaller than the Amazon review datasets for movies, music, and books.  This dataset has a bit over 221,000 reviews. The columns in the dataset are

| name           | description                                                                     |
|:-------------- |:------------------------------------------------------------------------------- |
| verified       | whether the reviewer bought the product from Amazon or not                      |
| reviewTime     | time of the review                                                              |
| reviewerID     | ID of the reviewer, e.g. A2SUAM1J3GNN3B                                         |
| asin           | ID of the product                                                               |
| reviewerName   | name of the reviewer                                                            |
| reviewText     | the text of the body of the review                                              |
| summary        | the test of the heading of the review                                           |
| unixReviewTime | time of the review (Unix time)                                                  |
| vote           | the number of times other reviewers thought the review helpful                  |
| style          | the attributes that vary -- for a example for a shirt it might be *medium blue* |
| image          | the associated image for the item.                                              |
| rating         | what we are trying to learn to predict a positive, neutral, or negative review. |

You are to develop a classifier that predicts the rating. 

The file with the training data is at http://34.82.108.37/amazonReviewsTrain.csv.zip

Once you are done training and tuning your classify you should run it on the test data.

The file with the test data is http://34.82.108.37/amazonReviewsTest.csv

Your predictions for the test set should be in a text file named `amazonReviewsPredictions.txt` that is placed in the same github directory as your Jupyter notebook file containing your code and comments.

The format of this predictions file should be

```
neutral
positive
positive
positive
neutral
neutral
positive
positive
positive
positive
...
```

To test the format of your output file you can use the following function:

```py
def test():
  i = 0
  answers = ['negative', 'neutral', 'positive']
  with open('amazonReviewsPredictions.txt', 'r') as outfile:
    lines = outfile.readlines()
    for line in lines:
        if line.strip() not in answers:
          return("invalid entry line %i" % (i))
        i += 1
    if i != 10000:
      return ("incorrect number of lines")
    else:
      return ("file looks ok")
test()
```

### XP

| xp   | rubric                                                                                |
| ----:|:------------------------------------------------------------------------------------- |
| 0    | code does not run and general approach looks misguided                                |
| 50   | code does not run but the general idea looks good.                                    |
| 75   | code runs, approach seems reasonable, **good description of approach in comments.**** |
| +25  | at least 7,000 correct predictions for the test dataset.                              |
| +50  | at least 7,500 correct                                                                |
| +75  | at least 8,000 correct                                                                |
| +100 | at least 8,500 correct    `                                                           |
| ++   | positional bonuses for the top 5 in class                                             |
