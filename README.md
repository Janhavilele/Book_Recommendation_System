# Book_Recommendation_System

Model will find appropriate book to read next based on his interest using  Nearest Neighbor algorithm.In this Collaborative filtering is used.

_**Steps :**_

**1) Data Collection :**
Download the dataset from kaggle (https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset) which contains 3 csv files namely Books.csv, Users.csv, Ratings.csv.

**2) Data Cleaning :**
- Consider those users who give minimum 200 ratings and remove other.
- Join the ratings and books dataset on ISBN.
- Consider those books which have minimum 50 ratings.

**3) Training the model :**
- Nearest neighbor algorithm used.
- Take k = 5

**4) Test the model:**
- Test the created model.
- Model give 95% accuracy.
