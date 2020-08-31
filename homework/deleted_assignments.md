7. Download 100 abstracts (at least 100 words per abstract) from PubMed that have `schizophrenia` and another 100 that have `dementia` in the title. Split randomly into 100 for a training set and 100 for a test set. Train a machine learning algorithm of your choice to predict the group (schizophrenia or dementia) from the abstract. Show a confusion matrix and ROC plot of the test sample predictions. Blog.
9.  Provide a [Google AI Platform](https://cloud.google.com/ai-platform/prediction/docs/deploying-models) website using [TensorFlow Serving](https://www.tensorflow.org/tfx/guide/serving) that allows the user to get a predicted classification of an uploaded image as beetle, cockroach or dragonfly. (This assumes you have done #7).