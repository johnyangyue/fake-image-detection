# Fake Image Detection

## Summary

We compare the classification performance impacts of dif- ferent combinations of image preprocessing techniques in the context of support vector machine and convolutional neural network. Our notable findings include

• Support vector machine’s performance is non-monotone with respect to input image resolution. Using low resolu- tion images can not only reduces computational cost, but also yield decent performance.

• Edge detection negatively affect support vector machine’s performance. Fake images might be defined by pixel value anomalies, not contour or shape anomalies.

• Convolutional neural network favors high input image resolution.

• Training data inconsistency due to randomness introduced by preprocessing techniques negatively affect detection performance.

Our research sheds some light on the ideal preprocessing practices that could be used for fake image detection. It also contributes to the model explainability literature by highlight- ing some of the elements in an image that are important to classification, which can help facilitate better model design.
