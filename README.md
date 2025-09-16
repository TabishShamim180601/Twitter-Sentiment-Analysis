1. Twitter sentiment analysis on a dataset obtained from Kaggle.  
2. The dataset comprises more than 74,682 training instances and 1,000 testing instances.  
3. The dataset comprised 4 classes: positive, negative, irrelevant and neutral.  
4. The "irrelevant" label was treated as "neutral". Thus, the number of classes was reduced to 3; positive, negative and neutral.  
5. The dataset had nearly equal distribution of classes with neutral class slightly dominating positive and negative classes in the training dataset  
6. TF-IDF was used as vectorisation technique.  
7. Linear SVC was chosen as model over kernel svm due to faster inference of linear svc on large datasets.
8. Multinomial Naive Bayes and Random Forest models were also utilised.
9. The final classification report showed nearly equal precision, recall and f1 scores for the 3 classes.
10. Random forest resulted in 95.1% accuracy while maintaining high precision and recall for each of the three classes. 
