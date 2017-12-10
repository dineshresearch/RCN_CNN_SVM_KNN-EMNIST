# Comparison of RCN/CNN/SVM/KNN on EMNIST-letters dataset


## Implementaions

* RCN: use reference implementation of [Recursive Cortical Network](https://github.com/vicariousinc/science_rcn)
* CNN: use [pytorch official example](https://github.com/pytorch/examples/tree/master/mnist) as reference architecture
* SVM
* KNN

## Dataset

Use [EMNIST](https://www.nist.gov/itl/iad/image-group/emnist-dataset) dataset for letters. (Cohen, G., Afshar, S., Tapson, J., & van Schaik, A. (2017). EMNIST: an extension of MNIST to handwritten letters. Retrieved from http://arxiv.org/abs/1702.05373)

> EMNIST Letters: 145,600 characters. 26 balanced classes.


You need to download dataset from EMNIST website to run the code. [This script](EMNIST/convert_mnist_to_bmp.py)(modified from https://github.com/Coopss/EMNIST) can be used to convert `emnist-letters.mat` to image files.
