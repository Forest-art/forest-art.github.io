---
title: "Xi'an Food and Attraction Classification Competition---Rank:11/723"
excerpt: "Detailed classification of various foods and attractions in Xi'an <br/><img src='/images/xian.png'>"
collection: portfolio
---



## Task
Huawei provides about 1,000 pieces of data, including food such as steamed buns, spinach noodles, and various attractions such as the Big Wild Goose Pagoda and the Small Wild Goose Pagoda. We need to design a classification model to classify pictures and rank them according to the classification accuracy.





## We Do
* Data augmentation: crawl online data and use various data augmentation algorithms such as transformation, distortion, and erasure.
* Model construction: Select several basic classification models for experimental comparison, and use EfficentNet as the backbone network.
* Optimization: use triplet loss as the loss function, which has a better effect on images with high similarity; freeze part of the network layer parameter training.