# YOLO
Training on SVHN http://ufldl.stanford.edu/housenumbers/
Exploration to see how good YOLO is.

## Getting started
1. python setup.py build_ext --inplace
2. flow --model cfg/yolo-10c.cfg --train --annotation annotation/train --dataset image/train
    - You can add the --load [path_to_file] flag if you have pre-trained weights to use.

## Notes
* annotation/test contains ALL xml files, while annotation/test_* contains subsets of those xml files to train on smaller datasets.
* Annotations can be found at: https://github.com/penny4860/svhn-voc-annotation-format
* Images can be found at SVHN Format 1: http://ufldl.stanford.edu/housenumbers/
* Darkflow can be found at: https://github.com/thtrieu/darkflow
* Pretrained weights:
    * https://pjreddie.com/media/files/yolov3.weights
    * https://drive.google.com/drive/folders/0B1tW_VtY7onidEwyQ2FtQVplWEU
