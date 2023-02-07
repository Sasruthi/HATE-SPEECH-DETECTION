# HATE-SPEECH-DETECTION
      
      Hate speech is extremely common on platforms such as Twitter, Facebook, comment sections, and even blogs or biased online publications, and even though things like profanity filters exist, they only filter out obscenities and swear words. 
      We find that the vast majority of hate speech consists of veiled attacks or otherwise uses words that would in other contexts be completely innocuous but are being used to attack an individual or group. 
      Most of even this is contextualized, so to know the context of each of the sentences and then gauge the hatefulness with near-perfect accuracy would require some knowledge of the topic under discussion, which is beyond the scope of our rule-based algorithm. 
      However, we discover a model to distinguish between speech that is mildly or intensely hostile and identify it with a fair degree of precision.



FLOW OF THE PROJECT

 1 Tweet pre-processing (removal of stop words, emojis, mentions, urls, and other noise, as well as a lemmatizing and stemming stage).
 
 2 Use the TF-IDF vectorizer to convert the data into a model of numerical features that are ready to be used for classification.
 
 3 Train five different ML classifiers using the training vectors with a splitting factor of 0.2.
 
 4 Tune some of the parameters of the best classifier among five to improve the model's accuracy.
 
 5 Use the best estimator of the selected classifier to predict the test labels.
 
CLASSIFIERS USED

Logistic Regression                   Accuracy = 89.75%
Random Forest Classifier              Accuracy = 89.75%
Linear Support Vector Classifier      Accuracy = 89.33%
AdaBoost Classifier                   Accuracy = 93.56%
XGBoost Classifier                    Accuracy = 89.79%

After tuning the best model (AdaBoost), model accuracy increases to 95.6%.
