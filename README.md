# DeepLearning_Fashion_Classification

The goal of the project is to apply deep learning to computer vision. Particularly, worked with the classification problem on a fashion compatibility dataset called Polyvore. Goals were to set up a category classifier and fashion compatibility classifier.

Another task was to predict the compatibility of an outfit. It’s essentially a binary classification problem (compatible or incompatible), however, the difficulty of the task lies in the input–classify based on a set rather than a single item. One idea to deal with set classification was to decompose it into pairwise predictions. Therefore, first trained a pairwise compatibility classifier.

Dataset Description : 
Polyvore Outfits is a real-world dataset created based on users’ preferences of outfit configurations on an online website named polyvore.com: items within the outfits that receive high-ratings are considered compatible and vice versa. It contains a total of 365,054 items and 68,306 outfits. The maximum number of items per outfit is 19.


data.py: dataset preparation
utils.py: utility functions and config
