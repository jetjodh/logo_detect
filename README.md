# logo_detect

* The training process took a very long time and more time would increase the accuracy much further.
* The notebooks will work only when placed in the unzipped folder for its dependencies. 
* For testing on a video source, I created a test video with randomly selected images from the test set and predicted the classes on it.
* The EfficientDets are a family of object detection models, which achieve state-of-the-art 55.1mAP on COCO test-dev, yet being 4x - 9x smaller and using 13x - 42x fewer FLOPs than previous detectors. The models also run 2x - 4x faster on GPU, and 5x - 11x faster on CPU than other detectors. But they take too long to train(days) to get a good accuracy and better generalization.
* The EfficientDets use EfficientNet as the network backbone which are also SoTA on ImageNet and are pretty fast.
* More Details to be added
