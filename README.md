# Machine Learning using the Amazon Customer Reviews data set
Amazon has released a dataset of labelled fake/real reviews: https://s3.amazonaws.com/amazon-reviews-pds/readme.html

This notebook uses Machine Learning and classification methods from NLTK and sklearn to learn and predict from this dataset, in particular training a Support Vector Machine (SVM) classifier

Using the review text alone the best `[precision, recall, fscore]` we were able to obtain was:
```
[0.6112074377868859, 0.6105357142857143, 0.6102143961844734]
```

By adding the features RATING, VERIFIED_PURCHASE and PRODUCT_TITLE, we were able to improve this to:
```
[0.8007384140998066, 0.8005714285714285, 0.8005548081465619]
```

See comments and markdown with the .ipynb for further details
