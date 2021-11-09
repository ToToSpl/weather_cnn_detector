# Weatcher CNN detector
CNN classifier of weather based on images. Done during university course

## Where to obtain data
Data on which the network was trained and tested can be downloaded from [here](https://www.kasprowski.pl/datasets/weather.zip). Uncompressed folder should be in the same directory as solution notebooks.

## Difference between notebooks
Better notebook uses libraries for one hot encoding, shuffling and managing test and train data, which makes it more readable and better, as more functions are available.

Improvement in network was also achieved by reducing it size, by deleting one convolutional layer and decreasing the size of fully connected network we decrease the chaince of over-training.