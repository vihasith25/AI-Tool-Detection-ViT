# 🔧 AI Tool Detection using Vision Transformers

## 📌 Overview

This project implements a **Vision Transformer (ViT)** model for mechanical tool image classification. The model is fine-tuned on a custom dataset of mechanical tools and demonstrates strong performance in identifying tool categories for industrial and automation-related applications.

By leveraging the self-attention mechanism of Vision Transformers, the model effectively captures image features and achieves high classification accuracy.

---

## 🚀 Features

- Fine-tuned Vision Transformer (ViT) model
- Mechanical tool image classification
- Transfer learning using Hugging Face Transformers
- Confusion Matrix visualization
- ROC Curve analysis
- Training and validation loss monitoring
- High classification accuracy and AUC score

---

## 🛠️ Tech Stack

- Python
- PyTorch
- Hugging Face Transformers
- Scikit-Learn
- NumPy
- Matplotlib
- Google Colab

---

## 📂 Dataset

**Dataset:** Mechanical Tools Dataset (Kaggle)

### Dataset Statistics

| Metric | Value |
|----------|----------|
| Total Images | 2400 |
| Training Images | 1920 |
| Testing Images | 480 |
| Classes | 3 |
| Image Size | 224 × 224 |

Images were preprocessed using the ViT Image Processor and converted to RGB format before training.

---

## 🧠 Model Architecture

### Pre-trained Model

```python
google/vit-base-patch16-224-in21k
```

### Training Configuration

| Parameter | Value |
|------------|---------|
| Epochs | 3 |
| Batch Size | 16 |
| Learning Rate | 2e-5 |
| Optimizer | AdamW |
| Framework | Hugging Face Trainer |

---

## 📊 Results

### Performance Metrics

| Metric | Score |
|----------|----------|
| Accuracy | 87% |
| Average AUC | 97% |

### Evaluation Techniques

- Classification Report
- Confusion Matrix
- ROC Curves
- Training Loss Analysis
- Validation Loss Analysis

---

## 📈 Visualizations

### Confusion Matrix

The confusion matrix highlights the model's classification performance and identifies misclassification patterns among tool categories.

### ROC Curves

The model achieved an average **AUC Score of 97%**, demonstrating strong discriminative capability.

### Training and Validation Loss

Training converged successfully within 3 epochs with stable validation performance.

---

## 🖼️ Sample Outputs

### Confusion Matrix

![Confusion Matrix](images/confusion_matrix.png)

### ROC Curve

![ROC Curve](images/roc_curve.png)

### Training Loss

![Training Loss](images/training_loss.png)

> Replace the image paths with your actual screenshots.

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/vihasith25/ai-tool-detection-vit.git
cd ai-tool-detection-vit
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the project:

```bash
python train.py
```

---

## 📁 Project Structure

```text
├── dataset/
├── models/
├── notebooks/
├── images/
├── train.py
├── requirements.txt
└── README.md
```

---

## 🎯 Applications

- Industrial Automation
- Smart Manufacturing
- Robotics
- Quality Inspection
- Inventory Management
- Automated Tool Recognition

---

## 🔮 Future Enhancements

- Increase the number of tool categories
- Train on larger datasets
- Compare ViT with CNN-based architectures
- Deploy as a Flask/FastAPI application
- Real-time tool detection using webcam input

---

## 🏆 Key Achievements

✅ Achieved **87% Accuracy**

✅ Achieved **97% AUC Score**

✅ Successfully fine-tuned a pre-trained Vision Transformer

✅ Demonstrated the effectiveness of transformer-based image classification

---

## 👨‍💻 Author

### Ranga Vihasith

**B.Tech – Computer Science & Engineering (AI & ML)**

Python | Machine Learning | Deep Learning | Computer Vision | Data Analytics

---

⭐ If you found this project useful, consider giving it a star!
