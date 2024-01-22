#Artificial Neural Network and Deep Learning Projects (AN2DL)
This repository contains the implementation and documentation of two key challenges in the field of Artificial Neural Networks and Deep Learning. The projects demonstrate a practical approach to solving problems in image classification and time series forecasting.

#Challenge 1: Binary Image Classification
Overview
The first challenge focuses on binary image classification, distinguishing between healthy and unhealthy data.

Key Features
Data Preprocessing: Includes outlier detection to ensure data quality.
Data Augmentation: Implemented to enhance the model's ability to generalize.
Model Implementation: Utilized VGG16 for baseline model development.
Transfer Learning: Applied EfficientNetB0, pre-trained on the ImageNet dataset, to leverage existing learned patterns.
Fine-tuning: Conducted by unfreezing layers (except for BatchNormalization layers) to refine model performance on specific data.
#Challenge 2: Univariate Time Series Forecasting
Overview
The second challenge deals with forecasting univariate time series data, encompassing 48,000 variable-length series across 6 categories.

Key Features
Data Preparation: Replication for short time series that are below a specified window length.
Zero Padding: Employed to standardize input lengths.
Model Architecture:
Convolutional-BiLSTM: Leveraged for capturing complex temporal patterns.
Time2Vec-BiLSTM: Utilized for enhanced time series analysis.
Category-Based Training: Separate models trained for each of the 6 categories to specialize in category-specific patterns.
Ensembling: Implemented an attention-based ensemble technique to integrate insights from individual models.
