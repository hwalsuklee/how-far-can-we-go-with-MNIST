# How far can we go with MNIST??
A collection of implementations for 'how far can we go with MNIST' challenge, which has been held in [TF-KR](https://www.facebook.com/groups/TensorFlowKR) at April 2017.

<p align="center">
<img src='how-far-can-we-go-with-MNIST.jpg' height = '300px'>
</p>

## List of Implementations
### Kyung Mo Kweon
* Test error : 0.20%  
* Features : keras, esemble of 3 models (small VGG, small Resnet, very small VGG)
* https://github.com/kkweon/mnist-competition

### Junbum Cha
* Test error : 0.24%  
* Features : tensorflow, ensemble of 3 models (VGG-like with batch size 64/128, resnet 32layers), best accuracy with a single model is 99.74%, data augmentation (rotation, shift, zoom)
* https://github.com/khanrc/mnist

### Jehoon Shin
* Test error : 0.26%  
* Features : tensorflow, ensemble of 5 models obtained with different hyper-params and same architecture (4 conv-layers, 1 fc-layer), best accuracy with a single model is 0.9968 
* https://github.com/zeran4/mnist_trial_and_error/blob/master/lab-11-5-1-mnist_cnn_ensemble_layers_tensorflow-kr.py

### Owen Song
* Test error : 0.28%  
* Features : keras (theano-base), ensemble of 5 models obtained with different hyper-params and same architecture (6 conv-layers), data augmentation (elastic distortion) 
* https://nbviewer.jupyter.org/gist/woniesong92/dba0b16405ef8c4174db2082f914dd80

### Kiru Park
* Test error : 0.30%  
* Features : tflearn, ensemble of 11 models (5 conv-nets, 3 highway-nets, 3 rnn), weights for ensemble are also trained, data augmentation (shift, rotation, blur) 
* https://github.com/kirumang/mnist_kr

### Mintae Kim
* Test error : 0.35%  
* Features : keras, ensemble of 3 models obtained with different filter size and same architecture (VGG-like), best accuracy with a single model is 0.9959, data augmentation (shift, rotation) 
* (original) https://github.com/kimmintae/MNIST/blob/master/MNIST%20Competition/mnist_competition.ipynb
* (updated, 0.20% test error) https://github.com/kimmintae/MNIST/blob/master/MNIST%20Competiton_9980/mnist_competition_9980_Final.ipynb

### Juyoung Lee
* Test error : 0.37% 
* Features : tensorflow, a single model (conv3-conv3-conv3-pool-conv5-conv-conv5-conv5-conv7-conv7-fc-fc-fc-fc), data augmentation (elastic transform) 
* https://github.com/uptown/TF-Mnist

### Hyungchan Kim
* Test error : 0.38%  
* Features : tensorflow, a single model (conv5-conv5-conv5-conv7)
* https://github.com/kozistr/MNIST-Competition

### Taekang Woo
* Test error : 0.43%  
* Features : tensorflow, a single model (resnet with number of residual units 4)
* https://github.com/tkwoo/MNISTclassification

### Hc Chae
* Test error : 0.46%  
* Features : tensorflow, ensemble of 5 models obtained with same hyper-params and same architecture (VGG-like), best accuracy with a single model is 0.9935, data augmentation (scale, rotation) 
* https://github.com/chaeso/dnn-study

### Junhyun Lee
* Test error : 0.47%  
* Features : tensorflow, ensemble of 2 models (different conv-net architectures), data augmentation (vertical/horizontal flip) 
* https://github.com/LeeJunHyun/LeeJunHyun

### Sungsub Woo
* Test error : 0.48%  
* Features : keras, ensemble of 50 models obtained with same hyper-params and same architecture (3 conv-layers, 1 fc-layer), data augmentation ([infmnist](http://leon.bottou.org/projects/infimnist)) 
* https://github.com/sungchi/mnist/

### Byeongki Jeong
* Test error : 0.59%  
* Features : keras, a single model (conv5-conv5-pool-conv5-conv3-pool-conv3-conv3-pool-conv3-conv3-pool-fc-fc)
* https://github.com/ByeongkiJeong/MostAccurableMNIST_keras

### Sungho Park
* Test error : 0.64%  
* Features : keras, a single model (conv3-pool-conv3-pool-conv3-pool-fc)
* https://github.com/bart99/tensorflow/blob/master/mnist/mnist5.py

### Wonseok Jeon
* Test error : 0.70%  
* Features : tensorflow, a single model (conv5-pool-conv5-pool-fc)
* (original) https://github.com/wsjeon/DeepMNISTforExperts
* (updated) https://www.dropbox.com/sh/pnlyb3fqgghm3i6/AAARrOAdOhRa54YeyfqvfBfKa?dl=0

### Byungsun Bae
* Test error : 2.21%  
* Features : tensorflow, a single model (9 fc layers with skip connection), gradient-clipping
* https://github.com/ByungSunBae/BBSProject/blob/master/mnist_competition_dev_simple_fnl.py

### Hyun Seok Jeong
* Test error : 7.16%  
* Features : tensorflow, a single model (conv3-pool-conv3-pool-conv3-pool-fc-fc)
* https://gist.github.com/nicewook/44a57e24e46dd531681f973b433b7fd0

### Sung Kim
* Test error : 11.20% 
* Features : tensorflow, logistic regression
* https://github.com/hunkim/DeepLearningZeroToAll/blob/master/lab-07-4-mnist_introduction.py

## Acknowledgements
* You may need to download uploaded models *manually*, especially for the case that models are stored with Git LFS.
* Here are reference results for MNIST : http://rodrigob.github.io/are_we_there_yet/build/classification_datasets_results.html

<p align="center">
<img src='TF-KR.jpg' height = '200px'>
</p>
