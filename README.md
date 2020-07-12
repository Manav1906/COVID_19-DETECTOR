# COVID_19-DETECTOR
Creating a Covid_19 Detector using a deep learning CNN model on a dataset of X-rays.

We arranged the dataset of X-rays for both Covid_19 positive as well as the normal beings from kaggle and github resources link for which is provided in the Dataset resources file. The Dataset was extracted and filtered. Code for which from scratch is available in Dataset_Creator.ipynb file.
We have build a CNN based sequential model with four feature extraction Conv2D layers. This model ran at an accuracy of 97% on train set and an accuracy of 97.02% on validation set.

We could have used transfer learning model but due to less samples available for Covid_19 positive X-rays right now we have build a classification CNN model for creating a baseline predictions with more samples in future we can apply transfer learning and may be can increase our prediction accuracy.


