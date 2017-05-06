# How far can we go with MNIST??
A collection of implementations for 'how far can we go with MNIST' challenge, which has been held in [TF-KR](https://www.facebook.com/groups/TensorFlowKR) at April 2017.

## List of Implementations
### Kyung Mo Kweon
* Test accuracy : 0.9980
* Features : keras, esemble of 3 models (small VGG, small Resnet, very small VGG)
* https://github.com/kkweon/mnist-competition

### Junbum Cha
* Test accuracy : 0.9976
* Features : tensorflow, ensemble of 3 models (VGG-like with batch size 64/128, resnet 32layers), best accuracy with a single model is 99.74%, data augmentation (rotation, shift, zoom)
* https://github.com/khanrc/mnist

### Jehoon Shin
* Test accuracy : 0.9974
* Features : tensorflow, ensemble of 5 models obtained with different hyper-params and same architecture (4 conv-layers, 1 fc-layer), best accuracy with a single model is 0.9968 
* https://github.com/zeran4/mnist_trial_and_error/blob/master/lab-11-5-1-mnist_cnn_ensemble_layers_tensorflow-kr.py

### Owen Song
* Test accuracy : 0.9972
* Features : keras (theano-base), ensemble of 5 models obtained with different hyper-params and same architecture (6 conv-layers), data augmentation (elastic distortion) 
* https://nbviewer.jupyter.org/gist/woniesong92/dba0b16405ef8c4174db2082f914dd80

### Kiru Park
* Test accuracy : 0.9970
* Features : tflearn, ensemble of 11 models (5 conv-nets, 3 highway-nets, 3 rnn), weights for ensemble are also trained, data augmentation (shift, rotation, blur) 
* https://github.com/kirumang/mnist_kr

### Mintae Kim
* Test accuracy : 0.9965
* Features : keras, ensemble of 3 models obtained with different filter size and same architecture (VGG-like), best accuracy with a single model is 0.9959, data augmentation (shift, rotation) 
* https://github.com/kimmintae/MNIST/blob/master/MNIST%20Competition/mnist_competition.ipynb

### Juyoung Lee
* Test accuracy : 0.9963
* Features : tensorflow, a single model (conv3-conv3-conv3-pool-conv5-conv-conv5-conv5-conv7-conv7-fc-fc-fc-fc), data augmentation (elastic transform) 
* https://github.com/uptown/TF-Mnist

### Hyungchan Kim
* Test accuracy : 0.9962
* Features : tensorflow, a single model (conv5-conv5-conv5-conv7)
* https://github.com/kozistr/MNIST-Competition

### Taekang Woo
* Test accuracy : 0.9957
* Features : tensorflow, a single model (resnet with number of residual units 4)
* https://github.com/tkwoo/MNISTclassification

### Hc Chae
* Test accuracy : 0.9954
* Features : tensorflow, ensemble of 5 models obtained with same hyper-params and same architecture (VGG-like), best accuracy with a single model is 0.9935, data augmentation (scale, rotation) 
* https://github.com/chaeso/dnn-study

### Junhyun Lee
* Test accuracy : 0.9953
* Features : tensorflow, ensemble of 2 models (different conv-net architectures), data augmentation (vertical/horizontal flip) 
* https://github.com/LeeJunHyun/LeeJunHyun

### Sungsub Woo
* Test accuracy : 0.9952
* Features : keras, ensemble of 50 models obtained with same hyper-params and same architecture (3 conv-layers, 1 fc-layer), data augmentation ([infmnist](http://leon.bottou.org/projects/infimnist)) 
* https://github.com/sungchi/mnist/

### Byeongki Jeong
* Test accuracy : 0.9941
* Features : keras, a single model (conv5-conv5-pool-conv5-conv3-pool-conv3-conv3-pool-conv3-conv3-pool-fc-fc)
* https://github.com/ByeongkiJeong/MostAccurableMNIST_keras

### Sungho Park
* Test accuracy : 0.9936
* Features : keras, a single model (conv3-pool-conv3-pool-conv3-pool-fc)
* https://github.com/bart99/tensorflow/blob/master/mnist/mnist5.py

### Wonseok Jeon
* Test accuracy : 0.9930
* Features : tensorflow, a single model (conv5-pool-conv5-pool-fc)
* https://github.com/wsjeon/DeepMNISTforExperts

### Byungsun Bae
* Test accuracy : 0.9779
* Features : tensorflow, a single model (9 fc layers with skip connection), gradient-clipping
* https://github.com/ByungSunBae/BBSProject/blob/master/mnist_competition_dev_simple_fnl.py

### Hyun Seok Jeong
* Test accuracy : 0.9284
* Features : tensorflow, a single model (conv3-pool-conv3-pool-conv3-pool-fc-fc)
* https://gist.github.com/nicewook/44a57e24e46dd531681f973b433b7fd0

### Sung Kim
* Test accuracy : 0.8880
* Features : tensorflow, logistic regression
* https://gist.github.com/nicewook/44a57e24e46dd531681f973b433b7fd0

## Acknowledgements
* You may need to download uploaded models *manually*, especially for the case that models are stored with Git LFS.
* Here are reference results for MNIST : http://rodrigob.github.io/are_we_there_yet/build/classification_datasets_results.html
