# Search-for-similar-images
 Search for similar images in an arbitrary dataset

## Description
My approach to the problem of finding similar images in an arbitrary dataset.
The idea is to use the representations obtained by a pre-trained neural network
to obtain the sum vectors of each filter of the last convolutional layer for 
each image and then compare using a suitable proximity metric.

This approach works quite well for a large number of images, with the special exception
of those that are graphical sketches in the dataset. They require additional processing 
or the use of another neural network.

## How to use

To use it, just open the file with the .pynb extension. You also need to change the path 
and image file names if you are working with a different dataset.

Link to dataset: https://disk.yandex.ru/d/Hu-um0ASI6eAUg

