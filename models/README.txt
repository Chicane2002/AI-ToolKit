##  README for `models/`

```markdown
# Models

This folder contains implementations of machine learning and deep learning models.  
Each model is modular and can be imported directly for use in projects or experiments.

---

## Structure
- **ann/** → Artificial Neural Networks  
- **cnn/** → Convolutional Neural Networks  
- **rnn/** → Recurrent Neural Networks (LSTM, GRU)  
- **transformers/** → Transformer-based models (BERT, GPT, etc.)  

---

## Usage Example
```python
from models.ann.ann_pytorch import SimpleANN
from models.cnn.cnn_pytorch import SimpleCNN
