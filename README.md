🚦 Traffic Sign Classification (Mini Project - Y3S1)
Computer Vision / Python / Jupyter Notebook
Dataset: Chinese Traffic Sign Recognition Database (TSRD)
Platform: Google Colab | TensorFlow | Keras | OpenCV
Demo Included ✅

📂 Project Overview
This project aims to develop a real-time traffic sign classification system tailored for autonomous vehicles and ADAS (Advanced Driver Assistance Systems). By leveraging ensemble deep learning techniques, the system achieves a balance between high accuracy and computational efficiency, making it viable for real-world deployment.

🧠 Ensemble Model Architecture
The proposed model is a lightweight ensemble of three state-of-the-art CNNs:

📈 EfficientNetB0

📉 MobileNetV3Small

❌ Xception

Combined via Global Max Pooling + Dense layers with LeakyReLU, BatchNorm & Dropout

🧪 Key Results
Metric	Our Model	Prior State-of-the-Art
Accuracy	94.60%	96.41%
Total Parameters	28.15M	163.18M
Model Size	107 MB	622 MB
Accuracy Drop	❌ -1.81%	—
Size Reduction	✅ ~80%	—
![image](https://github.com/user-attachments/assets/d356cbfa-757c-42be-8b23-e2ff8b7308ca)

⚡ Significant reduction in model size with minimal drop in performance.

🧩 Novel Contributions
⚙️ Ensemble of lightweight CNNs fine-tuned on TSRD dataset.

🧪 80% parameter reduction with just 1.81% loss in accuracy.

🏎️ Suitable for real-time deployment in embedded systems.

🔁 Applied moderate oversampling to handle class imbalance.

📊 Comprehensive evaluation with confusion matrices, F1-scores, and learning curves.

📷 Demo Included **
