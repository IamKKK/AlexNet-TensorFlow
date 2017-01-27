# AlexNet implementation in TensorFlow

This program implements the AlexNet CNN architecture in TensorFlow. Training is done on the Pascal VOC 2012 dataset.

Reference: Krizhevsky, Alex, Ilya Sutskever, and Geoffrey E. Hinton. "Imagenet classification with deep convolutional neural networks." Advances in neural information processing systems. 2012.

## Usage

In the code there are a few paths that need to be set:

1. "pascal_voc_path" 	  --> The absolute directory of the Pascal VOC 2012 dataset
2. "labels_subdir"       --> The absolute directory of the training labels text files; there are 20 in the Pascal VOC dataset since there are 20 object classes
3. "valid_labels_subdir" --> The absolute directory of the validation labels text files; there are 20 in the Pascal VOC dataset since there are 20 object classes
4. "images_subdir"		  --> The absolute directory of the image files

Then training can be run using: python3 AlexNet.py
