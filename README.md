# 🧠 Pokémon Name Generator using MLP

![Python](https://img.shields.io/badge/Python-3.x-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-Deep%20Learning-red)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-green)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626)
![MLP](https://img.shields.io/badge/Model-MLP-purple)
![Language Model](https://img.shields.io/badge/Type-Character%20Level%20Language%20Model-success)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

A character-level language model built from scratch in **PyTorch** that learns naming patterns from Pokémon names and generates new Pokémon-inspired names one character at a time.

Inspired by Andrej Karpathy's **Neural Networks: Zero to Hero** series.

---

## 🚀 Project Overview

This project implements a character-level language model using a Multi-Layer Perceptron (MLP).

Given a sequence of characters, the model learns to predict the next character and gradually generates complete Pokémon-style names.

Example:

```text
[p][i][k] → [a]
[p][i][k][a] → [c]
[p][k][a][c] → [h]
...
```

---

## 🏗️ Model Architecture

```text
3 Character Context
        │
        ▼
 Character Embeddings
        │
        ▼
 Hidden Layer (tanh)
        │
        ▼
      Logits
        │
        ▼
     Softmax
        │
        ▼
 Next Character Prediction
```

---

## 🎮 Sample Generated Names

```text
cham.
hound.
hop.
flitle.
glash.
skartang.
machu.
flett.
happlett.
nectabutterior.
palafin.
haton.
crocks.
tox.
lile.
frigibarrok.
purus.
frigible.
pignite.
dred.
```

The model generates entirely new names by sampling from learned character probability distributions.

---

## 📊 Visualizations

The project includes:

- Character Embedding Visualization
- Training Loss Curve
- Generated Name Samples
- Interactive Prefix-Based Generation

These visualizations help explain how the model learns and generates text.

---

## 📚 Concepts Implemented

- Character-Level Language Modeling
- Embedding Layers
- Multi-Layer Perceptrons (MLPs)
- Forward Propagation
- Backpropagation
- Gradient Descent
- Cross-Entropy Loss
- Probability Distributions
- Text Generation by Sampling

---

## ⚙️ Tech Stack

| Technology | Purpose |
|------------|----------|
| Python | Programming Language |
| PyTorch | Deep Learning Framework |
| Matplotlib | Visualizations |
| Jupyter Notebook | Development Environment |

---

## 🎯 Key Learnings

Through this project I explored:

- Character embeddings
- Neural network training
- Probability-based text generation
- Optimization using gradient descent
- Language modeling fundamentals

---

## 🔮 Future Improvements

- Larger context windows
- Deeper architectures
- WaveNet-style models
- Recurrent Neural Networks
- Transformer-based language models

---

## 📁 Repository Structure

```text
pokemon-name-generator-mlp/
│
├── MLP_pokemon_name_generator.ipynb
├── pokemon_names.txt.txt
├── README.md
└── .gitignore
```

---

## 🙏 Acknowledgements

Special thanks to Andrej Karpathy for the outstanding **Neural Networks: Zero to Hero** series, which inspired and guided this implementation.

---

⭐ If you found this project interesting, consider giving it a star.
