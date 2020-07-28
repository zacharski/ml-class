# ML Basics

Hi all. Welcome to the module covering  basic ML techniques.

This module consists of a number of units. 

In the first we will develop some basic intuitions about classification problems

we will look at a simple ml algorithm called kNN or k nearest neighbors.

Once we understand how the algorithm works we will turn to working with it in Python Code. 



In order to do this, in fact in order to do any ML work, we need some basic skills with a handful of Python libraries including Numpy Pandas and sckikit-learn

## SLIDE Getting ready to code

Before doing any of that, let's talk for a bit about coding.



In this course we are going to be doing a lot of coding. And by "we are going to be doing a lot of coding coding" I really mean you. 



You see,

If you are trying to learn guitar, you won't learn it by watching guitar tutorial videos on YouTube. The key element is deliberative practice. It is not the hours you rack up watching YouTube videos, but the hours you spend practicing.  It's exactly the same in most other aspects of life, including coding. So in this series  of videos I will help you get started and give you some guidance, and then let you finish the exercises on your own. Blood, Sweat and Code

So what will we be working on? - sleeve for a C compiler. 

## SLIDE - colab

In this course we will be using colab. Google Colab is a free browser-based service that allows us to experiment with machine learning without the need for installing anything on our own machines, or for us to have any fancy hardware. 

We will will learn enough to start using it.

#### Jupyter

Colab uses what are called Jupyter Notebooks. Project Jupyter is a nonprofit that develops open source software. Jupyter Notebooks allows us to experiment with our machine learning code interactively. As you will see, these notebooks contain both executable blocks of code, and formated text documentation about the code.

#### Numpy

I mentioned in an earlier video that numpy is a Python library that adds support for large matrices and mathematical functions on those matrices.  

#### Pandas 

data manipulation and analysis.  You may already be familiar with both Numpy and Pandas. There are whole courses devoted to them. We are just going to cover the basics to help us get started in machine learning

#### scikit learn

Finally, scikit learn is a library that contains machine learning algorithms. Instead of writing our own algorithms we can use scikit learn. For example, we talked about kNN in a previous video. We will be using the kNN implementation in sklearn.



### habit

One habit that is useful to develop is to save and share both your code and your notes.  You can do that to a degree in Google Colab but 

We are going to be doing that in github

git - a version control system and as the name suggests, allows us to keep different versions of code and documents. This is handy when you make a horrendous mistake and you'd like to go back to a previous version.  You create a repository for a project you are working on either by yourself or with a team. This repository contains all the code and documentation for the project. and, again all the versions of code and documentation.

github is a cloud-based hosting service for hosting and managing git repositories. 

This website, inquiryum.com is hosted for free at github, and all the material for the course is also hosting there.





Everyone comes to this video with a different set of skills. Some people know numpy and pandas and others don't and some know github and others don't. If I assume all the viewers don't know it then I will bore those that do. On the other hand if I assume everyone knows it, I'll make the people that dont know it horribly lost. So I am choosing the middle way. I will sketch things out and if you need more information

### creating a git repository



we are going to be using the git repository to save our colab work.



demo github, 



1. create repository - add readme, license
2. almost all our work will be done between colab and github but we may want to create documents on our laptops.
3. clone repo.



### markdown typora



SLIDES

markdown is a lightweight text formating convention. that uses plain text files. instead of a propriety format like Word or Apple Pages.

It is used for readme files, and is the format used in Google Colab, 

We can edit the files in a plain text editor or one tailored for markdown like Typora.





and some content.

heading and subheading

Paragraphs - blank line

bold, italic, 



bulleted list

numbered list

image



Code



\sum_{x=1}x

$$

this is how they set up the DNN:
$$
\sum_{x=1}^{100}{(x_i+y_i)^{1\over2}}
$$


formula

Here is a formula



### Save this back to github



