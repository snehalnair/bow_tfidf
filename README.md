# bow_tfidf
This project follows the traditional techniques like the Bag of Words and tf-idf to represent words in a corpus in a numeric format for multilabel classification.

1. Load the data
For this study, we are using a kaggle data for Toxic Comment Classification Challenge. Lets load and inspect the data. This is multilabel classification problem where comments are classified by the level of toxicity: toxic / severe_toxic / obscene / threat / insult / identity_hate

2. Split the dataset into train, validation and test

3. Preprocess text

4. Transform text to a vector

Using BoW and tf-idf
  
5. Multilabel Classification
 
 Using oneVsRest Classifier
  
6. Evaluation
  
  We will using metrics like accuracy score and f1 score for evaluation.
  Accuracy Score: In multilabel classification, this function computes subset accuracy: the set of labels predicted for a sample must exactly match the corresponding set of labels in y_true.
  F1 score : The F1 score can be interpreted as a weighted average of the precision and recall, where an F1 score reaches its best value at 1 and worst score at 0. The relative contribution of precision and recall to the F1 score are equal. F1 score = 2 * (precision * recall) / (precision + recall)
