# 🛠️ Utils

This folder contains utility scripts and helper functions used across the models in the AI Toolkit.  
The goal is to avoid repeating code and make model training/evaluation smoother.

---

## 📌 Included Utilities
- **data_preprocessing.py** → Functions for loading and preprocessing datasets (e.g., MNIST, CIFAR-10, IMDB).  
- **metrics.py** → Common evaluation metrics like accuracy, precision, recall, F1-score.  
- **visualization.py** → Helper functions for plotting training curves and visualizing predictions.  

---

## 🚀 Usage Example
```python
from utils.data_preprocessing import load_mnist
from utils.metrics import accuracy_score
from utils.visualization import plot_loss_curve
