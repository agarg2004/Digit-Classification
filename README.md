# Digit-Classification
Digit Classification on MNIST dataset using CNN


# About the Dataset 

Dataset can be downloaded from: " [kaggle competitions download -c digit-recognizer](https://www.kaggle.com/competitions/digit-recognizer/data) "
The data files train.csv and test.csv contain gray-scale images of hand-drawn digits, from zero through nine.

Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total. Each pixel has a single pixel-value associated with it, indicating the lightness or darkness of that pixel, with higher numbers meaning darker. This pixel-value is an integer between 0 and 255, inclusive.

The training data set, (train.csv), has 785 columns. The first column, called "label", is the digit that was drawn by the user. The rest of the columns contain the pixel-values of the associated image.

# Predictions
The predictions.csv file contains the predictions on the train.csv file and contains 28000 rows with 2 columns ImageId and Label.

