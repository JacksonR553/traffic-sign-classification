# 🚦 Traffic Sign Classification (Mini Project - Y3S1)

**Computer Vision / Python / Jupyter Notebook**  
**Dataset**: Chinese Traffic Sign Recognition Database (TSRD)  
**Platform**: Google Colab • TensorFlow • Keras • OpenCV  
**Demo Included ✅**


## 📘 Project Overview

This project develops a **real-time traffic sign classification system** for autonomous vehicles and Advanced Driver Assistance Systems (ADAS).  
By leveraging **ensemble deep learning**, we ensure both **high classification accuracy** and **lightweight performance**, making it ideal for deployment on embedded systems.


## 🧠 Model Architecture

We use an ensemble of the following pretrained CNN models:

- ⚡ `EfficientNetB0`
- 📱 `MobileNetV3Small`
- ❌ `Xception`

These are combined via **Global Max Pooling**, followed by:
- `Dense Layers` with `LeakyReLU`
- `Batch Normalization`
- `Dropout` regularization

> Base layers are frozen (transfer learning) to reduce training time.


## ✅ Results Summary

| Metric               | Our Model     | Prior Work (ResNet50 + DenseNet121 + VGG16) |
|----------------------|---------------|---------------------------------------------|
| **Accuracy**         | 94.60%        | 96.41%                                      |
| **Model Size**       | 107.37 MB     | 622.49 MB                                   |
| **Total Parameters** | 28.15 M       | 163.18 M                                    |
| **F1-Score**         | 93.93%        | 96.16%                                      |
| **Precision**        | 95.08%        | 96.16%                                      |
| **Recall**           | 94.60%        | 96.16%                                      |

> 📉 **80% reduction in model size** with just **~1.8% accuracy drop**.


## 🧪 Project Highlights

- ✅ Lightweight ensemble model using transfer learning.
- 🔄 Moderate oversampling for rare traffic signs (RandomOverSampler).
- ⏱️ Grid search for hyperparameter tuning (batch size, learning rate, optimizers).
- 📉 Dropout + L2 regularization to reduce overfitting.
- 📊 Evaluation with confusion matrices, learning curves, and visual analysis.


## 📷 Demo Included **


## 👥 Contributors

Thanks to the amazing team who made this possible:

- [@chewliy](-)
- [@angqiaoyi](https://github.com/QiaoYi01)
- [@teohmingxue](https://github.com/JacksonR553)
- [@wongsumhui](-)

