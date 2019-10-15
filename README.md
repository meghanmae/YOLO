# YOLO
Training on SVHN http://ufldl.stanford.edu/housenumbers/
Exploration to see how good YOLO is.

## Getting started
1. python setup.py build_ext --inplace
2. flow --model cfg/yolo-10c.cfg --train --annotation annotation/train --dataset image/train [optional] --load bin/yolo.weights

## Notes
* annotation/test contains ALL xml files, while annotation/test_* contains subsets of those xml files to train on smaller datasets.