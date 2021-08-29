PATH OF THE DATASET:

IF DONE USING JUPYTER NOTEBOOK:
train = pd.read_csv('train.csv')
test = pd.read_csv('test.csv')

We have defined a function "drawImg(sample)", where sample=single array, 
which reshapes any single array to 28X28 matrix and gives us the image.
We use it to verify it with our predicted label data.

We have used: 
1) KNN, 2)KNN(BALL TREE), 3) SVM (LINEAR), 4) SVM (RBF) , 5) DECISION TREE, 6) RANDOM FOREST

Out of these RANDOM FOREST has given the maximum accuracy of 96.47% or accuracy_score of 0.9647.

So we conclude RANDOM FOREST is giving us the best accuracy among the above classifiers.

We have also kept the predicted labels from the "test.csv" into "submission.csv".
