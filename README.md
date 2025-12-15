# 🎨✨ Machine Learning & Deep Learning — by @Ritam-910

![GitHub Repo stars](https://img.shields.io/github/stars/Ritam-910/Machine-Learning-And-Deep-Learning?style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/Ritam-910/Machine-Learning-And-Deep-Learning?style=for-the-badge)
![GitHub issues](https://img.shields.io/github/issues/Ritam-910/Machine-Learning-And-Deep-Learning?style=for-the-badge)
![Made with Python](https://img.shields.io/badge/Made%20with-Python-blue?style=for-the-badge)

A compact, colourful collection of practical ML & DL notebooks, scripts, and utilities — built for learning, prototyping, and showcasing results with attractive visualisations. 🌈📊

---

Quick links
- About · Highlights · Notebooks · Examples · Contribute

About
A curated set of hands-on projects covering classification, regression, clustering, and basic deep learning. Each notebook focuses on clarity, reproducibility, and visual storytelling.

Highlights
- 🎓 Clear Jupyter notebooks with explanations
- 🧪 Reproducible scripts + checkpoints
- 📈 Beautiful visualisations (matplotlib / seaborn / plotly)
- ⚙️ Lightweight utilities: loaders, transforms, metrics
- 🚀 Starter templates for rapid experiments

Structure (short)
- notebooks/ — tutorials & demos  
- src/ — reusable modules (data, models, utils)  
- experiments/ — runnable training scripts  
- data/ — dataset notes / small samples  
- models/ — saved weights / checkpoints

Quick start
1. Clone
```bash
git clone https://github.com/Ritam-910/Machine-Learning-And-Deep-Learning.git
cd Machine-Learning-And-Deep-Learning
```
2. Install
```bash
python -m venv venv
source venv/bin/activate   # or .\venv\Scripts\activate (Windows)
pip install -r requirements.txt
```
3. Open a notebook
```bash
jupyter lab
# or open in Google Colab for GPU-enabled demos
```

Example snippets
- Train a classifier
```python
from src.data import load_csv
from src.models import train_classifier, evaluate

X, y = load_csv("data/sample.csv")
model = train_classifier(X, y)
evaluate(model, X, y)
```
- Visualise results
```python
from src.plot import plot_confusion_matrix, plot_learning_curve
plot_learning_curve(history)
plot_confusion_matrix(y_true, y_pred, classes=class_names)
```

Notebooks (selected)
- 01-exploratory-data-analysis.ipynb — colourful EDA  
- 02-classification-basics.ipynb — logistic & tree demos  
- 03-deep-learning-intro.ipynb — small CNN example  
- 04-clustering.ipynb — k-means visualisations

Contributing
Contributions welcome! Fork → branch → PR. Keep notebooks readable, remove large outputs, and include a short description of changes.

License & Contact
MIT License. Built with ❤️ by @Ritam-910 — open an issue or PR for suggestions or dataset requests.
