Automated Leukemia Classification System
An innovative deep learning initiative for identifying leukemia from microscopic blood cell images. This system accurately distinguishes between healthy cells (HEM) and leukemic cells (ALL) using advanced model architectures and optimized training strategies.
🌟 Project Summary  

Built with EfficientNet-B0, ResNet-50, and InceptionV3 architectures.  
Enhanced with multi-head attention, Leaky ReLU, and fine-tuning, achieving a remarkable 98.22% training accuracy and 94.06% validation accuracy.  
Utilizes the C-NMC leukemia dataset, comprising 15,135 labeled blood cell images.

🚀 Key Features  

Superior Accuracy: Outperforms conventional models in classifying leukemia.  
Advanced Enhancements: Customized EfficientNet-B0 with additional dense layers, batch normalization, and dropout for robustness.  
Reliable Training: Achieved stable convergence over 60 epochs, minimizing overfitting.  
Thorough Validation: Evaluated with precision, recall, F1-score, and confusion matrix metrics.

📂 Dataset  

Source: C-NMC Leukemia Dataset  
Details: 15,135 labeled images, split into:  
HEM: Healthy cells (Hematological Malignancies)  
ALL: Leukemic cells (Acute Lymphoblastic Leukemia)


Preprocessing: Applied normalization, augmentation (rotation, zoom, shear, flip), and noise reduction.

🖼 System Architecture  
Architecture Overview  

Input: Microscopic blood cell images.  
Preprocessing: Normalization, augmentation, and noise correction.  
Models: EfficientNet-B0, ResNet-50, and InceptionV3 with multi-head attention.  
Output: Binary classification (HEM or ALL).

⚙ ApproachPreprocessing  

Scaled pixel values to [0, 1].  
Augmented data with rotation, zoom, shear, and flip to enhance model generalization.

Models Employed  

EfficientNet-B0: Integrated multi-head attention and custom dense layers.  
ResNet-50: Leveraged transfer learning for feature extraction.  
InceptionV3: Employed for multi-scale feature capture.

Training  

Conducted over 60 epochs using the Adam optimizer, ensuring consistent loss reduction.  
Fine-tuned model layers for improved domain-specific performance.

Evaluation  

Assessed with precision, recall, F1-score, and confusion matrix for robust performance insights.

📊 Performance Metrics  



Model
Training Accuracy
Validation Accuracy



ResNet-50
84.50%
87.49%


EfficientNet-B0
85.95%
86.49%


InceptionV3
81.06%
81.86%


Proposed Model
98.22%
94.06%


The proposed model demonstrated exceptional accuracy and reliable classification, with minimal errors as shown in the confusion matrix.  
📄 Detailed ReportAccess the full project report here: Automated Leukemia Detection Report.  
🔧 Technical Requirements  

Python 3.7+  
TensorFlow 2.0+  
Keras  
NumPy  
Pandas  
Matplotlib

🧠 Skills ShowcasedDeep Learning Frameworks:  

TensorFlow  
Keras

Model Development:  

Transfer Learning  
EfficientNet-B0, ResNet-50, InceptionV3

Data Preprocessing:  

Image Normalization  
Augmentation (Rotation, Zoom, Shear, Flip)  
Noise Reduction

Model Evaluation:  

Precision, Recall, F1-score  
Confusion Matrix Analysis

📬 ContactFor inquiries, reach out via [insert contact method].
