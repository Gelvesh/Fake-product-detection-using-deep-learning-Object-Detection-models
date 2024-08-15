The repository was inspired by the research paper "ENHANCING FAKE PRODUCT DETECTION USING DEEP LEARNING OBJECT DETECTION MODELS" by Eduard Daoud, Dang Vu, Hung Nguyen and Martin Gaedke.
https://www.iadisportal.org/ijcsis/papers/2020150102.pdf

I have tried to SSD Mobile net + EfficientDet-D0 architectures.
The results were underwhelming since the training dataset was only <66 images, leading to incorrect detections in test images.

This can be improved by having more training dataset and use more training steps.
