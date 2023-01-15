# Face-Recognization-Model-using-varies-ML-Classifier

This Face Recognization Model is a ML Algorithm's based model where I used Olivetti Face dataset to train and test the model.
The Olivetti dataset consist of ten different images of each of 40 distinct subjects. For some subjects, the images were taken at different times, varying the lighting, facial expressions (open / closed eyes, smiling / not smiling) and facial details (glasses / no glasses).

The Image are of 64x64 pixel, and if downloaded from Sklearn Library it is already normalized and and contains data in numerical form.
I used three different models : Logistic Regression, Support Mector Machine Classifier and Naive Bayes Classifier to compare the performance of these algorithm by calculating the accuracy score and later cross validation score after applying cross-validationto improve result and avoid overfitting.
Apart from Numpy and matplotlib, I have used the Sklearn library and fetch the dataset using it. You can learn about its function and features from its official Website.

Final result was that logistic Regression and SVM were working fine but Naive Bayes Classifer was not fiiting good for this data.
