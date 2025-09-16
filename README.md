Twitter sentiment analysis on a dataset obtained from Kaggle.
The dataset comprises 15,000 training instances and 1,000 testing instances.
The dataset comprised 4 classes: positive, negative, irrelevant and neutral.
The "irrelevant" label was treated as "neutral". Thus, the number of classes was reduced to 3; positive, negative and neutral.
The dataset had nearly equal distribution of classes with neutral class slightly dominating positive and negative classes in the testing dataset (457 neutral as compared to 277 
positive and 266 negative).
TF-IDF was used as vectorisation technique.
Linear SVC was chosen as model over kernel svm due to faster inference of linear svc on large datasets.
The final classification report showed nearly equal precision, recall and f1 scores for the 3 classes.
