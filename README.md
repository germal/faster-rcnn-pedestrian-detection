# Pedestrian-RCNN

This code extends [py-faster-rcnn](https://github.com/rbgirshick/py-faster-rcnn) by adding:
  * ResNet implementation.
  * Online Hard Example Mining.
  * Caltech Dataset train and test interface. 

## Base

* The faster rcnn code is based on [py-faster-rcnn](https://github.com/rbgirshick/py-faster-rcnn).
* The ohem code is based on [ohem](https://github.com/abhi2610/ohem).
* To reduce the memory usage, we use batchnorm layer in [Microsoft's caffe](https://github.com/Microsoft/caffe)
* The caltech dataset interface based on [GBJim-py-faster-rcnn](https://github.com/GBJim/py-faster-rcnn)

