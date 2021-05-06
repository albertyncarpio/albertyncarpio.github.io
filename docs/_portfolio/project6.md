---
title: Project Name
subtitle: Using Image Processing Techniques to Improve the Performance of Non-Neural Network Image Classification
image: https://raw.githubusercontent.com/BlackrockDigital/startbootstrap-agency/master/src/assets/img/portfolio/01-full.jpg
alt: Fashion Image Processing

caption:
  title: Window
  subtitle: Using Image Processing Techniques to Improve the Performance of Non-Neural Network Image Classification
  thumbnail: https://raw.githubusercontent.com/BlackrockDigital/startbootstrap-agency/master/src/assets/img/portfolio/01-full.jpg
---
Fashion is a global industry that is a popular, ubiquitous means of self-expression. A fashion clothing classification model would significantly help in the inventory of fashion industry. In addition, incorporating image-based searches for e-commerce sites such as Shopee, Lazada, and Amazon would improve the site's recommendation system.

Usually computer vision problems default as applications for convolutional neural networks (CNN) however, the model complexity may make further application cumbersome.  For this project, then, we experiment with using a Random Forest Classifier on our fashion dataset. This project wanted to answer, "Can we improve the performance of non-neural network machine learning methods by data augmentation using image processing?".

We used two means of data augmentation using image processing: edge detection and region properties.  We ran the experiment on four scenarios: A baseline using only the reduced original dataset; a setup using the reduced datasets from both the original and edge images; a setup only on the region properties; and finally a model using all three inputs.  Our best model was the one trained on the stacked reduced original and reduced edge datasets, with a train score of $78.7\%$ and a validation score of $78.3\%$.  Second best was the model using all the data augmentation.

We went on to evaluate this model on its test score and the standard classification metrics. The model had average recall, precision, and f1-score results of $77.3\%$ against the test dataset.  The model performs best when classifying trousers, bags, and ankle boots, and falters when trying to classify shirts.


{:.list-inline}
**Co-creators:**
[Rafael Madrigal](https://www.linkedin.com/in/raf-madrigal)
[Queenie Mendez](https://www.linkedin.com/in/queenie-lynly-mendez)
