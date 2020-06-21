# Image-classification-into-3-categories
Classify image into 3 categories: Night; Portrait(face); Landscape


Here, the images are to be classified into 3 categories : Human Face(potrait), Night, Landscape.
The basic Bag of visual words (BOVW) is used in image classification.

The general idea of bag of visual words (BOVW) is to represent an image as a set of features. Fea-
tures consists of keypoints and descriptors. SIFT descriptor is used for extracting features, keypoints
in the image. Next, clusters from the descriptors are made using K-Means clustering algorithm. The
center of each cluster will be used as the visual dictionary’s vocabularies. Finally, for each image, fre-
quency histogram is made from the vocabularies and the frequency of the vocabularies in the image.
Those histograms are our bag of visual words (BOVW).

This histograms used for comparing and then finding the best match for an image using K-Nearest
Neighbour model. The accuracy obtained with this model was 73.33%.
