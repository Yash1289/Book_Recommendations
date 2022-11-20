
![Logo](https://www.transparentpng.com/thumb/book-png/G2ritw-book-opened-pages-transparent-image.png)


# Book Recommender System

Recommendation systems are widely used today to recommend products to users based on their interests. A recommendation engine is one of the most vital systems for increasing profits by retaining more users in a big competition. Online book reading and selling websites like Kindle and Goodreads compete against each other on many factors. One of those crucial factors is their book recommendation system. A book recommendation system is designed to recommend books of interest to the buyer. In this project, I have built a Book Recommender system using data extracted from books selling websites to recommend similar books to the reader based on his interest


## Install

This project requires Python and the following Python libraries installed

* [NumPy](https://numpy.org/)
* [Pandas](https://pandas.pydata.org/)
* [Matplotlib](https://matplotlib.org/)
* [Seaborn](https://seaborn.pydata.org/)
* [scikit-learn](https://scikit-learn.org/stable/)
* [Surprise](https://surpriselib.com/)

We also need to have software installed to run and execute a Jupyter Notebook.

We can install the [Anaconda](https://www.anaconda.com/) distribution of python
which already has most of the above packages and more included or we can also run the 
whole notebook on google colab without going through the process of installing all the
libraries locally in our machine.


## Code

The main code is provided in the `Book_Recommender_System.ipynb`
notebook file. We will also require three datasets namely `Books.zip`,
`Ratings.zip` and `Users.zip`, all three of them needs to be unzipped first 
to get the csv file out of them using which we can run the notebook properly.

## Run

In a terminal or command window, navigate to the top-level project directory (that contains this README) 
and run one of the following commands:

```
ipython notebook Book_Recommender_System.ipnyb
```
or
```
jupyter notebook Book_Recommender_System.ipnyb
```
or open with Jupyter Lab
```
jupyter lab
```
This will open the Jupyter Notebook software and project
file in our browser
## Data

In this project we have three datasets `Books.csv` , `Ratings.csv` and
`Users.csv` . The Books dataset is containing a total of 271360 different
records and also 8 different features associated with each of them.

### Features

    1.  Book-Title : The title of the book
    2.  ISBN : International Standard Book Number 
    3.  Book-Author : The author of the book
    4.  Year-Of-Publication : The year in which this edition of the book was published
    5.  Publisher : The Publishing house who published the book
    6.  Image-URL-L : URL linking to large size cover image of the book
    7.  Image-URL-M : URL linking to medium size cover image of the book
    8.  Image-URL-S : URL linking to small size cover image of the book

The Users dataset is containing info of around 278858 users along with 3 features.

### Features

    1. User-ID : The anonymized user id of the users
    2. Age : The age of the user
    3. Location : This contains the city, state and country of the user

The number of records in Ratings dataset is 1149780 , with each datapoint
having 3 features

### Features

    1. User-ID : The anonymized user id of the users
    2. ISBN : International Standard Book Number
    3. Book-Rating : This contains the book rating information , ratings are either explicit or implicit expressed by zeroes.


## 🛠 Algorithms Used
Collaborative Filtering , Singular Value Decomposition , Gradient Descent,
K nearest neighbors 
## Authors

- [@Yash1289](https://github.com/Yash1289)


## 🚀 About Me
I'm an aspiring Data Scientist who is adept in analyzing and interpreting large datasets and developing new forecasting models. I have strong attention to detail and a significant ability to work in team environments.


## 🔗 Links
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shaurabh-pandey-69484921a/)


