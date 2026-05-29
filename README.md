# Generalization of Image Classfication Model on Distorted Data

This repository examines the accuracy and precision of deep image classfication models when faced with distorted data. We train models on 5 types of 
of images with varying types of distortion, undistorted, gaussian noise, gaussian blur, salt and pepper noise, and a mix of all 3 distortions.

We then evaluate how these models generalize to other types of distortion, as well as how the precision of these models differ. We also evaluate
the efficacy of an ensemble of the gaussian noise, gaussian blur, and salt and pepper noise trained models against just the model trained on
a mix of the 3 distortions.
