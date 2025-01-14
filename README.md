# Active millimeter-wave concealed object detection dataset
# Introduction

Active millimeter-wave (AMMW) imaging technology is a promising approach for detecting concealed objects carried by individuals for security screening applications. To facilitate advancements in the object detection of the AMMW images, we build a large-scale public open dataset, namely ACODD, comprising 20,004 image samples of human bodies with eight different categories of concealed objects. The data is available for free to researchers for non-commercial use. All images and data will be released publicly in this GitHub repo.

# Overview

The dataset is collected by a near-range MIMO-SAR AMMW imaging system with a scanned single-input-single-output linear array. The operating frequency is 24.4 GHz to 27.8 GHz, with a range resolution of 5 cm and a cross-range resolution of 5 mm. The depth of the region of interest ranges from 0.2 m to 0.5 m from the antenna array, and the cross-range dimensions of the region of interest are 1.8 m * 0.96 m, producing 15 equidistant layers of images in the depth dimension with 440 * 840 pixels for each layer. The dataset comprises 20004 images collected by 66 unique volunteers with 64 different poses. The front view and back view images of the same test subject are paired in the dataset. There are 8 different types of objects with different materials and sizes, including model guns, fruit knives, folding knives, lighters, baby oil, powder, rectangular explosives, and disc-shaped explosives.

The statistics of the occurrences of various concealed objects in the dataset.

|  | Model Gun | Fruit <br> Knife | Folding <br> Knife | Lighter | Baby Oil | Powder | Rectangular <br> Explosive | Disc-shaped <br> Explosive | Total |
|---|---|---|---|---|---|---|---|---|---|
| Total | 2842 | 2202 | 2580 | 2774 | 2350 | 2462 | 2320 | 2474 | 20004 |  

<img src=sample.svg width ='1000'>

Sample display for each category. The bottom row shows a zoomed-in view of the object.

# Download links

The dataset is not currently available because the data is part of an ongoing study. It will be made public in this GitHub repo as soon as possible.

# Privacy

Informed consent was obtained from all participants prior to data collection.

# License

Active millimeter-wave concealed object detection dataset (ACODD) by XGJZ is licensed under CC BY-NC-SA 4.0
