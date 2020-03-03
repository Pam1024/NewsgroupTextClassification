# NewsgroupTextClassification

dataset: https://scikit-learn.org/0.19/datasets/twenty_newsgroups.html

*  **Collocation extraction**. 
  1. Tokenize this corpus and perform part-of-speech tagging on it. 
  2. Apply the techniques  (Frequency with filter, PMI, T-test with filter, Chi-Sq test) to extract bigram collocations from the corpus. 

*  **SVM and NB for Text Classification**
  1. Remove stop words. 
  2. Remove numbers and other non-letter characters. 
  3. Stem the words. 
  4. Convert the corpus into a bag-of-words tf-idf weighted vector representation.  
  5. Train Multinomial NB and report confusion matrix.   
  6. Train SVM and report confusion matrix. 
  7. Repeat above actions on raw data and compare the performace with above result.
  

