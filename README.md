# Stack_overflow_tags_prediction
Prediction of the tags for stack overflow post headings using tf-idf vectorization and Ridge Classifier. Bag-of-words model was tried as a substitute for tf-idf and logistic regression as a substitute for Ridge Classifier and the difference in performances were evaluated.

Ridge regression has two main benefits. First, adding a penalty term reduces overfitting. Second, the penalty term guarantees that we can find a solution. Ridge regression uses l2 penalty as a regularization term and the loss function is the linear least squares function. Loss function of cross entropy is used in logistic regression.

Bag-of-words does not take care of the relative position or sequence of words in a text, it just counts frequency of words in a text. Tf-idf takes care of the word-relevancy by counting the frequency of words in the text(document) and in the entire corpus. tf-idf for word k in document j = number of times k appeared in j/(log(number of documents/number of documents having word k))
