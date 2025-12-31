# Deep Learning Course Portfolio  
### End-to-End Neural Network Projects in NLP, Computer Vision & Model Optimization

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-Keras-orange)
![Deep Learning](https://img.shields.io/badge/Deep%20Learning-NLP%20%7C%20CV%20%7C%20Optimization-brightgreen)
![NLP](https://img.shields.io/badge/NLP-BERT%20%7C%20Word2Vec-purple)
![Computer Vision](https://img.shields.io/badge/Computer%20Vision-CNN%20%7C%20Augmentation-green)
![Deployment](https://img.shields.io/badge/Deployment-TensorFlow%20Lite-red)
![Status](https://img.shields.io/badge/Status-Interview%20Ready-success)

---

**Author:** Tirumala Teja Yegineni  
**Audience:** Recruiters • Hiring Managers • Technical Interviewers  
**Purpose:** Course Portfolio • Resume-focused • Interview-ready • Explainable  

---

## 📌 Overview

This repository documents **all projects completed as part of a Deep Learning course**, implemented using **Jupyter notebooks** and modern deep learning frameworks.

The portfolio demonstrates a **complete learning-to-application pipeline**, starting from **core neural network theory**, moving through **applied NLP and computer vision**, and ending with **deployment-oriented model optimization**.

Key focus areas:
- Correct **model architecture selection**
- Strong **evaluation practices**
- Handling **real-world data challenges**
- Preparing models for **production and edge deployment**

Each notebook represents a **standalone mini-project**, making this repository ideal for **interview walkthroughs** and **resume discussions**.

---

## 🧠 Skills Demonstrated (Recruiter Snapshot)

- Deep learning model development using **TensorFlow/Keras**
- Natural Language Processing with **BERT, Word2Vec, and supervised embeddings**
- Computer Vision with **CNNs and data augmentation**
- Handling **imbalanced datasets** using correct metrics (precision, recall)
- Model optimization using **TensorFlow Lite quantization**
- Strong foundations in optimization, regularization, and evaluation

**ATS Keywords:**  
Deep Learning, Neural Networks, TensorFlow, Keras, CNN, NLP, BERT, Transformers, Word2Vec, Embeddings, Data Augmentation, Quantization, TFLite, Imbalanced Learning, SMOTE, Precision Recall, Confusion Matrix

---

# 📂 Projects Completed in This Course (Detailed)

---

## 1️⃣ BERT Email Classification (Spam Detection)

**Notebook:** `BERT_email_classification.ipynb`  
**Dataset:** `spam.csv`

### Objective
Build a modern NLP classifier to detect spam emails using transformer-based embeddings.

### Work Performed
- Integrated **BERT embeddings** via TensorFlow Hub
- Added a custom neural classification head
- Trained and validated the model on labeled email data

### Concepts Demonstrated
- Transformer architectures
- Transfer learning in NLP
- Binary text classification
- Model evaluation and validation

---

## 2️⃣ Telecom Customer Churn Prediction (Imbalanced Dataset)

**Notebook:** `Telecom Churn prediction and imbalanced dataset.ipynb`

### Objective
Predict customer churn in a **highly imbalanced real-world dataset**.

### Work Performed
- Data preprocessing and categorical encoding
- Applied **SMOTE and class weighting**
- Evaluated models using **precision, recall, and confusion matrix**

### Concepts Demonstrated
- Imbalanced learning
- Metric-driven model evaluation
- Business-focused ML decision-making

---

## 3️⃣ Handwritten Digit Classification

**Notebook:** `Hand written Digit Classification.ipynb`

### Objective
Classify handwritten digits using neural networks.

### Work Performed
- Built a dense neural network architecture
- Trained using Adam optimizer
- Analyzed accuracy and loss convergence

### Concepts Demonstrated
- Multi-class classification
- Neural network fundamentals
- Optimization techniques

---

## 4️⃣ Image Classification using Convolutional Neural Networks

**Notebook:** `image classification using CNN.ipynb`

### Objective
Extract spatial features from images using CNNs.

### Work Performed
- Designed CNN architectures with Conv2D and MaxPooling
- Compared **SGD vs Adam** optimizers
- Evaluated validation performance

### Concepts Demonstrated
- CNN architecture design
- Feature extraction
- Optimizer selection

---

## 5️⃣ Data Augmentation in Deep Learning

**Notebook:** `Data augmentation in deep learning.ipynb`

### Objective
Improve model generalization and reduce overfitting.

### Work Performed
- Applied image augmentation techniques
- Compared training results with and without augmentation

### Concepts Demonstrated
- Regularization via augmentation
- Overfitting mitigation
- Generalization improvement

---

## 6️⃣ Quantization in Deep Learning (TensorFlow Lite)

**Notebook:** `Quantization in deep learning.ipynb`

### Objective
Optimize deep learning models for **deployment on resource-constrained environments**.

### Work Performed
- Converted trained models to **TensorFlow Lite**
- Implemented post-training quantization and quantization-aware training (QAT)
- Compared performance and accuracy trade-offs

### Concepts Demonstrated
- Model compression
- Edge deployment readiness
- Performance vs accuracy analysis

---

## 7️⃣ Supervised Word Embedding Model

**Notebook:** `supervised word embedding.ipynb`

### Objective
Learn word embeddings as part of a supervised NLP task.

### Work Performed
- Used Keras `Embedding` layer
- Trained embeddings end-to-end with a classifier

### Concepts Demonstrated
- Representation learning
- Embedding layers
- NLP fundamentals

---

## 8️⃣ Word2Vec Experiments (Gensim)

**Notebooks:**  
- `word2vec sports dataset.ipynb`  
- `word2vec cellphones dataset.ipynb`

### Objective
Learn semantic relationships between words using distributional semantics.

### Work Performed
- Trained Word2Vec models
- Performed similarity and vector space analysis

### Concepts Demonstrated
- Word embeddings
- Semantic similarity
- Vector space analysis

---

## 9️⃣ Core Deep Learning Theory & Metrics

**Notebooks Include:**
- Activation functions and loss functions
- SGD and mini-batch gradient descent
- Precision, recall, confusion matrix
- Dropout regularization

### Objective
Build strong theoretical foundations for deep learning.

---

## 🔄 Suggested Interview Walkthrough Order

1. BERT Email Classification (modern NLP)
2. CNN Image Classification + Data Augmentation
3. Quantization & TensorFlow Lite (deployment focus)
4. Telecom Churn Prediction (imbalanced learning)

---

## ⚙️ How to Run Locally

```bash
python -m venv .venv
# Windows
.venv\Scripts\activate
# macOS/Linux
source .venv/bin/activate

pip install numpy pandas matplotlib seaborn scikit-learn tensorflow tensorflow-hub \
            gensim imbalanced-learn pillow opencv-python jupyterlab

jupyter lab
```

---

## 🧾 Detailed Resume Bullet Points (Copy-Paste Ready)

- Completed a **comprehensive Deep Learning course portfolio** covering **NLP, computer vision, imbalanced learning, and deployment optimization**, implemented using **TensorFlow/Keras**.  
- Designed and trained **CNN-based image classification models**, applying **data augmentation and regularization** techniques to improve generalization and reduce overfitting.  
- Implemented **transformer-based NLP models (BERT)** for email spam detection, leveraging **transfer learning** and evaluating performance using industry-standard metrics.  
- Built and evaluated classifiers for **highly imbalanced datasets**, applying **SMOTE and class weighting** and prioritizing **precision–recall metrics** over raw accuracy.  
- Developed **word embedding models** using both **Keras Embedding layers** and **Word2Vec (Gensim)** to analyze semantic relationships in text data.  
- Optimized trained neural networks for deployment by implementing **TensorFlow Lite post-training quantization and quantization-aware training**, demonstrating an understanding of **edge deployment constraints**.  
- Demonstrated strong theoretical grounding in **activation functions, loss functions, optimization algorithms (SGD, Adam), and regularization (dropout)** through targeted experimental notebooks.

---

## 👤 Author

**Tirumala Teja Yegineni**  
GitHub: https://github.com/TIRUMALA9999
