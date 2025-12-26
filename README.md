# 📘 Assignment 2: Supervised Learning – Support Vector Machine (SVM)
 
## 👥 Group Assignment  
This assignment explores the **Support Vector Machine (SVM)** algorithm using the **WorkhoursProductivity** dataset to enable a direct performance comparison.
 
---
 
## 🧠 Part 1: Familiarization and Basic Testing of SVM 
 
### 📊 Dataset Selection 
- We used the **WorkhoursProductivity** dataset.
- This allowed us to directly compare **kNN vs. SVM** performance under similar conditions.
- The dataset contains labeled data suitable for supervised classification.
 
---
 
### ⚙️ Algorithm Application 
- Implemented SVM using **`sklearn.svm.SVC`**.
- Tested multiple kernels to observe performance differences:
  - 🔹 **Linear Kernel**
  - 🔹 **Polynomial Kernel**
- The model was trained and evaluated using standard train-test splits.
 
---
 
### 🌍 Real-World Applications of SVM 
Support Vector Machines are highly effective in **high-dimensional spaces**, making them suitable for:
 
1. 📰 **Text Classification**  
   - Spam detection  
   - Sentiment analysis  
   - Document categorization  
 
2. 🧬 **Bioinformatics**  
   - Gene classification  
   - Cancer detection using high-dimensional medical data  
 
---
 
## 🔬 Part 2: In-Depth Experimentation with SVM 
 
### 🎛️ Parameter Experimentation 
- Experimented with different values of **C (regularization parameter)**:
  - Low C → More regularization, simpler decision boundary
  - High C → Less regularization, more complex boundary
- Observed that:
  - ⚠️ Very high C may cause overfitting
  - ✅ Moderate C values provided better generalization
 
---
 
### 🔁 Kernel Comparison 
We compared at least two kernels on the same dataset:
 
| Kernel Type | Observations |
|------------|--------------|
| **Linear** | Faster training, works well when data is linearly separable |
| **Polynomial** | Captures non-linear patterns but may overfit with higher degrees |
 
---
 
## 📈 Findings & Observations ✅
 
- 🆚 **SVM generally performed better than kNN** on this dataset, especially with optimal parameter tuning.
- 🧩 **Kernel choice significantly impacts performance**:
  - Linear kernel worked well for simpler patterns
  - Polynomial kernel improved accuracy for non-linear relationships
- 🎯 SVM is more **robust to high-dimensional data** compared to kNN.
- ⚖️ Proper tuning of **C** is critical to balance bias and variance.
 
---
 
## 🛠️ Tools & Libraries Used
- 🐍 Python
- 📦 Scikit-learn
- 📊 NumPy
- 📈 Matplotlib / Seaborn (for visualization)
 
---
 
## 📌 Conclusion
SVM is a powerful supervised learning algorithm that:
- Excels in high-dimensional spaces
- Offers flexibility through kernel functions
- Often outperforms distance-based methods like kNN when properly tuned
 
This assignment demonstrates how **parameter tuning and kernel selection** directly influence SVM performance.
 
