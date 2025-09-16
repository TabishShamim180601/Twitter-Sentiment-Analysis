1. Twitter sentiment analysis on a dataset obtained from Kaggle.  
2. The dataset comprises more than 70,000 training instances and 1,000 testing instances.  
3. The dataset comprised 4 classes: positive, negative, irrelevant and neutral.  
4. The "irrelevant" label was treated as "neutral". Thus, the number of classes was reduced to 3; positive, negative and neutral.  
5. The dataset had nearly equal distribution of classes with neutral class slightly dominating positive and negative classes in the testing dataset (457 neutral as compared to 277 positive and 266 negative).  
6. TF-IDF was used as vectorisation technique.  
7. Linear SVC was chosen as model over kernel svm due to faster inference of linear svc on large datasets.  
8. The final classification report showed nearly equal precision, recall and f1 scores for the 3 classes.  
