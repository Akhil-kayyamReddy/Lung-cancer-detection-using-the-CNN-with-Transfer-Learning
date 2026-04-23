🧠 Lung Cancer Detection using CNN with Transfer Learning (EfficientNet-B5)
📌 Overview

This project aims to detect lung cancer from CT scan images using deep learning. It utilizes transfer learning with EfficientNet-B5 to achieve high accuracy while minimizing training time and computational cost.

The model classifies medical images into cancerous and non-cancerous categories, supporting early diagnosis and reducing manual effort in healthcare analysis.

🚀 Features
Transfer Learning using EfficientNet-B5
Image preprocessing (Histogram Equalization, Contrast Enhancement)
Binary classification (Cancer / Non-Cancer)
Performance evaluation using Accuracy, Precision, Recall, F1-score
Reduced overfitting using Dropout and fine-tuning
🛠️ Tech Stack
Language: Python
Libraries: TensorFlow, Keras, NumPy, Pandas, OpenCV, Matplotlib
Model: EfficientNet-B5 (Pretrained on ImageNet)
Environment: Jupyter Notebook / Google Colab
🧬 Model Architecture
Base Model: EfficientNet-B5
Global Average Pooling layer
Fully Connected Dense layers
Dropout for regularization
Sigmoid activation for binary classification
📊 Results
Achieved high classification accuracy on validation data
Improved performance compared to traditional CNN models
Efficient training due to transfer learning

(Add your actual metrics here if available)

📂 Project Structure

├── dataset/
├── notebooks/
├── models/
├── utils/
├── results/
├── requirements.txt
└── README.md


💡 Future Improvements
Multi-class classification (cancer stages)
Deployment using Flask/React
Integration with hospital systems
Larger and diverse dataset

🎯 Use Case
Assists doctors in early lung cancer detection
Reduces manual diagnosis time
Supports data-driven healthcare decisions

📜 License
This project is for educational and research purposes.
