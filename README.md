# CNN_project
# Predict if the page is being flipped or not.. 

We trained two models to predict if a page is being flipped using a single image. The first model utilized the TinyVGG architecture, and the second model used transfer learning from the timm library with the resnet34 model. The TinyVGG model achieved an F-score of 0.97, while the second model achieved an F-score of 1. When we plotted the training and testing accuracy and loss, we observed that the first model was more stable and had a better fit than the pretrained model.

Additionally, we tested the TinyVGG model with a new dataset, consisting of images taken with a camera, and found that its predictions were accurate. Based on our goal to predict if a page is being flipped using a single image, we have determined that the best model is the first one, which achieved an F1 score of 0.97.
