# 🍌🍉 Fruit Classification Using SVM and PCA 🍉🍌

## 🚀 Project Overview  
This project focuses on classifying fruit images, specifically distinguishing between **Banana** and **Watermelon** 🍌🍉, using classical machine learning techniques. It demonstrates the application of Support Vector Machine (SVM) combined with Principal Component Analysis (PCA) for dimensionality reduction to tackle high-dimensional image data effectively.

## 🎯 Objectives  
- Build a lightweight and efficient binary classifier for fruit images.  
- Apply image preprocessing steps like resizing, grayscale conversion, normalization, and feature scaling.  
- Handle class imbalance and optimize hyperparameters for SVM using GridSearchCV.  
- Use PCA to reduce feature dimensionality and improve model accuracy.

## 📦 Dataset  
- Source: [Fruit Classification (10 Classes) on Kaggle](https://www.kaggle.com/datasets/karimabdulnabi/fruit-classification10-class)  
- Focused Classes: Banana and Watermelon only.  
- Preprocessing: Images resized to 128x128 pixels, converted to grayscale, flattened, normalized, and standardized.

## 🧠 Model Details  
- Algorithm: Support Vector Machine (SVM) with RBF kernel.  
- Hyperparameter tuning via GridSearchCV for optimal **C** and **gamma** values.  
- Class imbalance addressed with `class_weight='balanced'`.  
- Dimensionality reduction through PCA to avoid overfitting and improve speed.

## 📊 Results  
- Initial accuracy without PCA: ~24%  
- Improved accuracy with PCA: ~60%  
- Confusion matrix indicated better recognition for Banana class.  
- Challenges included high dimensionality, class imbalance, and training time.

## 🔧 Tools & Libraries  
- Python  
- scikit-learn  
- NumPy & pandas  
- PIL (Python Imaging Library)  
- Google Colab for development and testing

## 💡 Lessons Learned  
- Effective preprocessing and dimensionality reduction are critical in image-based classical ML tasks.  
- Hyperparameter tuning significantly impacts SVM performance.  
- Handling real-world dataset challenges such as imbalance and high dimensionality.

## 🚀 Future Improvements  
- Expand classification to include more fruit types for multi-class classification.  
- Explore deep learning models for improved accuracy and robustness.  
- Optimize the pipeline for faster training and deployment.

## 🔗 Links  
- Dataset: [Kaggle Fruit Classification](https://www.kaggle.com/datasets/karimabdulnabi/fruit-classification10-class)  

---

**Developed by Layan Atta** 👩‍💻  
Machine Learning Enthusiast | Data Scientist  

---

