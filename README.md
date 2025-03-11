# 📝 Signature Recognition using CNN  

This project implements a **Convolutional Neural Network (CNN)** for **signature recognition**. The model processes handwritten signature images, segments them per person, and classifies them into different categories. The model performance is evaluated using **accuracy, precision, recall, and F1-score**, and compared with other feature extraction methods.  

---

## 🚀 **Features**  
✔ Loads a dataset of **handwritten signatures**  
✔ **Preprocesses** images (grayscale conversion, resizing, normalization)  
✔ Performs **train-test split** for model training  
✔ Builds and trains a **CNN model** for classification  
✔ Compares CNN-based feature extraction with **HOG/SIFT**  
✔ Evaluates model performance using **Accuracy, Precision, Recall, F1-score**  
✔ Plots **training vs validation loss & accuracy**  
✔ Visualizes **sample predictions**  

---

## 🔧 **Requirements**  
- Python  
- Jupyter Notebook  
- Pytorch  
- OpenCV (for image processing)  
- Matplotlib & Seaborn (for visualization)  

---

## 📊 **Results & Evaluation**  
The CNN model was trained and evaluated on a dataset of signatures. The following metrics were used for evaluation:  
✔ **Accuracy**  
✔ **Precision & Recall**  
✔ **F1-score**  

Comparison with **HOG and SIFT** feature extraction techniques was also conducted to determine the best-performing approach.  
