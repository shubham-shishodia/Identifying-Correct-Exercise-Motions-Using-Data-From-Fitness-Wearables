# Read Me

The goal of this project is to identify how well people do a particular weightlifting exercise, by analyzing data collected from accelerometers attached to the belt, arms and dumbbells. The data consists of exercise movements of 6 different indivduals, who were asked to perform the exercise under supervision. The outcomes were classified into 5 different categories, with class A being the correct technique, and the other classes categorizing common mistakes. The dataset, and relevant information about it was made available by the work of Wallace Ugulino, Eduardo Velloso and Hugo Fuks, and can be downloaded from http://web.archive.org/web/20161224072740/http:/groupware.les.inf.puc-rio.br/har.

The approach used for creating a classification model was as follows:

1. Load the dataset
2. Partition the dataset into training and validation sets
3. Perform exploratory analysis on the training set
4. Build a model on the training set
5. Evaluate model performance on the validation set
6. Perform predictions on the test set
