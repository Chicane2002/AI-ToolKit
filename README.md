# AI Toolkit

A personal **toolbox of AI and Machine Learning models** implemented in TensorFlow and PyTorch.  
This repository is designed as a plug-and-play toolkit to quickly access models (ANN, CNN, RNN, Transformers, etc.), along with utilities and example workflows.

---

## Repository Structure



---

## 🔑 Features
- Plug-and-play **ANN, CNN, RNN, Transformer** implementations  
- Supports both **TensorFlow** and **PyTorch**  
- Preprocessing, visualization, and evaluation utilities  
- Example notebooks for datasets like MNIST, CIFAR-10, and IMDB  
- Modular and expandable design  

---

### 1. Clone the repo
```bash
git clone https://github.com/your-username/AI-toolkit.git
cd AI-toolkit
### 2. Install dependencies
bash
Copy code
pip install -r requirements.txt
### 3. Example usage
python
Copy code
from models.cnn.cnn_pytorch import SimpleCNN
from utils.data_preprocessing import load_mnist

X_train, y_train, X_test, y_test = load_mnist()
model = SimpleCNN()
# Train / Evaluate here

## Models Included
ANN – Dense feedforward networks

CNN – Image classifiers (LeNet, simple CNNs)

RNN – LSTM, GRU for sequence modeling

Transformers – BERT/GPT finetuning (coming soon)

## Roadmap
1. Add pretrained checkpoints

2. Config-driven training

3. CI/CD tests with GitHub Actions

4. Publish as pip package

## Contributing
This is a personal repo to be used when snippets of code are needed.

## License
MIT License – free to use and modify.
