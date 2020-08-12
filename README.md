# Tooth detection on panoramic radiograph images with Faster RCNN model
This is a repo for the mini-project dealing with tooth detection in realistic situations, characterized with relatively small number (in this case, 114 panoramic radiographs) of images for training object detection models, with differing qualities (contrasts, lightness) and sizes. The objective of the work is to define the pipeline and framework of decisions in x-ray images object detection problems. Faster RCNN architecture is used for detection; the approach includes transfer learning, augmentation and normalization (Contrast Limited Adaptive Histogram Equalization) of x-ray images. Resulting model performance is comparable with or exceeding the state of the art in the field, with mean Average Precision for the test set of mAP=0.96-0.97.
