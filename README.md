🧠 Autism Spectrum Disorder (ASD) Image Classification with Deep Learning

---

📘 **Introduction**

This project explores whether deep learning models can distinguish between autistic and non-autistic facial images using image-based classification. The goal is to evaluate how different neural network architectures perform on a controlled image dataset.

This project was completed as a final project for **IST 691 – Deep Learning** in the Master of Applied Data Science program at Syracuse University.

---

🎯 **Motivation**

Early research has explored whether facial features contain patterns that machine learning models can learn in controlled settings. While not intended for diagnosis, this study investigates the technical feasibility and limitations of image-based classification approaches for ASD-related research.

---

📊 **Dataset**

- Image dataset of facial photographs labeled as autistic or non-autistic  
- Dataset used strictly for academic research purposes  
- Preprocessing included resizing, normalization, and train/validation/test splitting  

⚠️ The dataset is **not included** in this repository due to privacy and ethical considerations.

---

⚙️ **Methodology**

- **Exploratory Data Analysis (EDA)** to understand class distribution and image characteristics  
- **Image Preprocessing**: resizing, normalization, and augmentation  
- **Model Architectures**:
  - Custom CNN trained from scratch
  - MobileNetV2 using transfer learning
- **Evaluation Metrics**:
  - Accuracy
  - Precision & Recall
  - ROC–AUC
  - Confusion Matrix

---

📈 **Key Results**

- The custom CNN achieved slightly higher test accuracy (~81%)
- MobileNetV2 demonstrated faster convergence but greater instability during fine-tuning
- Both models showed non-trivial misclassification, highlighting dataset limitations and domain sensitivity

---

📁 **Repository Contents**

- `ASD_Classification_Notebook.ipynb` – Model training, evaluation, and analysis  
- `ASD_Classification_Report.pdf` – Final written report  

---

🛠 **Tools & Technologies**

- Python  
- TensorFlow / Keras  
- Google Colab  
- NumPy, Pandas, Matplotlib  

---

⚠️ **Disclaimer**

This project is exploratory and intended for academic research only. Facial image–based classification is **not** a clinical diagnostic tool, and results should not be interpreted as medical conclusions.
