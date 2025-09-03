# Task-3-SVM


---

## 🚀 Project Overview

1. **Download the dataset** from Kaggle using the Kaggle API
2. **Preprocess images**: resize to 64x64 pixels and convert to grayscale
3. **Flatten images** into vectors to feed into the SVM
4. **Train an SVM classifier** on a subset of the data (to save time)
5. **Evaluate** the model and print classification report & accuracy
6. **Visualize** sample predictions

---

## ⚙️ How to Run in Google Colab

1. Upload your Kaggle API key file `kaggle.json` when prompted  
2. Run all cells step-by-step  
3. Dataset will be downloaded and extracted automatically  
4. Model will train and evaluate on the data subset  

---

## 📦 Requirements

- Python 3.x  
- Packages: `opencv-python`, `numpy`, `scikit-learn`, `tqdm`, `matplotlib`

All dependencies are installed automatically in the notebook.

---

## 🧠 Notes

- SVM works best on smaller datasets and simple feature vectors  
- Images are converted to grayscale and flattened to reduce dimensionality  
- For better results, consider using feature extraction techniques like HOG or CNN-based deep learning models  

---

## 📊 Sample Output
     Cat       0.84      0.87      0.85       200
     Dog       0.86      0.83      0.84       200

accuracy                           0.85       400


