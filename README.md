# 📌 Abstract
Acute Lymphoblastic Leukemia (ALL) is a rapidly progressing cancer that requires swift and accurate diagnosis to improve patient 
outcomes. Traditional diagnostic methods, although effective, are invasive, costly, and time-intensive, leading to the need for more 
efficient approaches. In this study, we propose an advanced tri-layer deep learning model to automate ALL diagnosis using Peripheral 
Blood Smear (PBS) images. Our approach integrates three innovative stages: (1) Segmentation using ResNet50, which isolates relevant 
regions with high precision, (2) Feature Extraction with EfficientNet B0 V2, capturing intricate cell details essential for classification, 
and (3) Final Classification using CNN, distinguishing between benign and malignant cells, including three subtypes of ALL—Early 
Pre- B, Pre-B, and Pro-B. The performance metrics as a highly reliable, efficient, and scalable solution for early ALL diagnosis, 
offering significant promise for real-time clinical implementation and transforming cancer screening methodologies.

# 🔗 Dataset Link  
[Download from Kaggle](https://www.kaggle.com/datasets/mehradaria/leukemia)  

# Hardware Requirements
- **Google Colab:** No local hardware required, runs in the cloud.
- **Local Setup:** Minimum 8GB RAM (Recommended: GPU with NVIDIA GTX 1650 or better for deep learning tasks).

# Software Requirements
- **Operating System:** Windows / Linux / macOS
- **Python Version:** 3.8+ required
- **Google Colab:** Runs in a browser, no installation needed

# Running on Google Colab
1. Open [Google Colab](https://colab.research.google.com/).
2. Upload the `.ipynb` notebook or open it directly from GitHub.
3. Install required dependencies (if not pre-installed) by running:
   ```python
   !pip install -r requirements.txt

pip install numpy pandas matplotlib seaborn scikit-learn tensorflow torch opencv-python

