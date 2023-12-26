# AN2DL Projects
 Artificial Neural Network and Deep Learning Projects



First Challenge was about binary image classification on labelled(healthy and unhealthy) data.

->Data Preprocessing including outlier detection
->Data Augmentation Implemented
->VGG16 Model Used
->Transfer Learning Implemented Using EfficientNetB0 trained on ImageNet Dataset
->Fine Tuning Implemented Unfreezing Layers Except for BatchNormalization Layers


Second Challenge was about univariate time series forecasting on 48000 variable-length time series data that has 6 different categories

-> Data Replication for short time series(below window)
-> Zero Padding Used
-> Convolutional-BiLSTM and Time2Vec-BiLSTM models used.
-> Models trained category based, in total 6 models(one model for each category).
-> Attention based ensembling implemented.