---
title: Passion for Fashion
subtitle: Using Image Processing Techniques to Improve the Performance of Non-Neural Network Image Classification
image: https://images.pexels.com/photos/322207/pexels-photo-322207.jpeg
alt: Fashion Image Processing

caption:
  title: Passion for Fashion
  subtitle: Using Image Processing Techniques to Improve the Performance of Non-Neural Network Image Classification
  thumbnail: https://images.pexels.com/photos/322207/pexels-photo-322207.jpeg
---
Fashion is a global industry that is a popular, ubiquitous means of self-expression. A fashion clothing classification model would significantly help in the inventory of fashion industry. In addition, incorporating image-based searches for e-commerce sites such as Shopee, Lazada, and Amazon would improve the site's recommendation system.

Usually computer vision problems default as applications for convolutional neural networks (CNN) however, the model complexity may make further application cumbersome.  For this project, then, we experiment with using a Random Forest Classifier, augmented with image processing techniques, on our fashion dataset

We used two means of data augmentation using image processing: edge detection and region properties.  We ran the experiment on four scenarios: A baseline using only the reduced original dataset; a setup using the reduced datasets from both the original and edge images; a setup only on the region properties; and finally a model using all three inputs.  Our best model was the one trained on the stacked reduced original and reduced edge datasets, and second best was the model using all the data augmentation.

{:.list-inline}
**Co-creators:**
[Rafael Madrigal](https://www.linkedin.com/in/raf-madrigal)
[Queenie Mendez](https://www.linkedin.com/in/queenie-lynly-mendez)
