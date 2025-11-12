# Deep Learning Methods for Medical Visualization – Labs

This repository contains all lab material for the course **Deep Learning Methods for Medical Visualization**.  
The labs guide you from basic supervised learning to advanced deep learning pipelines for medical image analysis.

## Labs overview

### Lab 1 – Supervised Learning & Medical Image Analysis

- Review supervised learning concepts (training, validation, test, overfitting)
- Work with simple classification or regression examples in Python
- Connect machine learning tasks to typical medical imaging problems  
  (e.g. lesion detection, organ classification, disease prediction)

### Lab 2 – ANN and DNN Fundamentals

- Implement a multilayer perceptron from scratch or with TensorFlow/Keras
- Use common activation functions and loss functions
- Train with gradient descent–based optimizers and monitor training curves
- Study underfitting/overfitting and regularization on small image datasets

### Lab 3 – CNNs for Medical Images

- Understand convolution, filters, padding and pooling
- Build and train a basic CNN for 2D medical images  
  (e.g. slices from MRI/CT/X-ray)
- Compare CNN performance to fully connected networks on the same task
- Inspect learned feature maps and discuss their relation to image patterns

### Lab 4 – Medical Image Segmentation with CNN (U-Net)

- Implement or reuse a U-Net-style architecture in TensorFlow
- Prepare image–mask pairs, patching and resizing for segmentation
- Use segmentation loss functions (e.g. cross-entropy, Dice loss)
- Evaluate with Dice score / IoU and visualize predicted masks

### Lab 5 – Medical Image Classification with CNN

- Train a deeper CNN for disease or tissue classification
- Apply data preprocessing and augmentation tailored to medical images
- Use metrics such as accuracy, sensitivity, specificity, ROC and AUC
- Discuss class imbalance and strategies to handle it

### Lab 6 – RNNs for Medical Image Analysis

- Introduce sequence modelling (RNN, LSTM, GRU) for medical data
- Work with temporal or ordered data  
  (e.g. image sequences, time series, reports)
- Build an RNN model in TensorFlow and connect it to a clinical task
- Evaluate and compare to non-sequential baselines

### Lab 7 – Transfer Learning and Deep Features

- Use pre-trained CNNs (e.g. ImageNet models) for medical image classification
- Perform feature extraction vs fine-tuning
- Analyze training speed, performance and data requirements
- Export deep features and use them in classical ML models  
  (e.g. SVM, Random Forest)

### Lab 8 – Interpretability & Recent Deep Learning Methods

- Apply interpretation and visualization techniques  
  (e.g. saliency maps, Grad-CAM, feature visualization)
- Explore recent architectures or methods for medical image analysis
- Critically evaluate model performance, robustness and clinical relevance
- Summarize findings in a short written or presentation-based report
