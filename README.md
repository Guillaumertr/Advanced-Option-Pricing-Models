# 🧠 Advanced Option Pricing with Monte Carlo & Deep Learning

This repository presents four Jupyter Notebooks implementing advanced methods for pricing American-style options using simulation-based algorithms.

Each notebook explores a different method — from classical tree-based techniques to modern neural network approaches — with the goal of accurately pricing and hedging complex derivative instruments in high dimensions or under market frictions.

---

## 📚 Notebooks Overview

### 1. 📈 Binomial Tree & Monte Carlo — `Binomial_Option_Pricing.ipynb`

This notebook implements a **Cox-Ross-Rubinstein binomial tree model** combined with **Monte Carlo simulation**.

✅ Features:
- Backward induction using the binomial tree.
- Optimal stopping region visualization.
- Monte Carlo pricing from the derived stopping rule.

🔍 Ideal for:
- Understanding early exercise features.
- Visualizing option exercise boundaries.

---

### 3. 🔬 Longstaff-Schwartz with Neural Network — `Longstaff-Schwartz_NeuralNetwork_Option_Pricing.ipynb`

This notebook extends the **Longstaff-Schwartz** algorithm (LSM) by replacing regression on basis functions with a neural network.

🧠 Key Contributions:
- Neural networks approximate continuation values.
- Better capture of non-linear payoff structures.
- Works well in high-dimensional state spaces.

📦 Includes:
- Custom PyTorch model.
- Per-time-step training loop.
- Confidence interval estimation.

---

### 2. 📊 Longstaff-Schwartz with Regression — `LongStaffSchwartz_Regression_Option_Pricing.ipynb`

This is a faithful implementation of the **original LSM algorithm** by Longstaff & Schwartz (2001), using various basis functions for regression.

⚙️ Features:
- Polynomial, Augmented, and Hermite basis sets.
- Visualization of approximated value functions.
- Confidence intervals for the option price.

💡 Best suited for:
- Benchmarking more advanced methods.
- Studying the impact of basis choice on pricing accuracy.

---

# 🧠 Advanced Option Pricing with Monte Carlo & Deep Learning

This repository presents four Jupyter Notebooks implementing advanced methods for pricing American-style options using simulation-based algorithms.

Each notebook explores a different method — from classical tree-based techniques to modern neural network approaches — with the goal of accurately pricing and hedging complex derivative instruments in high dimensions or under market frictions.

---

## 📚 Notebooks Overview

### 1. 📈 Binomial Tree & Monte Carlo — `Binomial_Option_Pricing.ipynb`

This notebook implements a **Cox-Ross-Rubinstein binomial tree model** combined with **Monte Carlo simulation**.

✅ Features:
- Backward induction using the binomial tree.
- Optimal stopping region visualization.
- Monte Carlo pricing from the derived stopping rule.

🔍 Ideal for:
- Understanding early exercise features.
- Visualizing option exercise boundaries.

---

### 2. 📊 Longstaff-Schwartz with Regression — `LongStaffSchwartz_Regression_Option_Pricing.ipynb`

This is a faithful implementation of the **original LSM algorithm** by Longstaff & Schwartz (2001), using various basis functions for regression.

⚙️ Features:
- Polynomial, Augmented, and Hermite basis sets.
- Visualization of approximated value functions.
- Confidence intervals for the option price.

💡 Best suited for:
- Benchmarking more advanced methods.
- Studying the impact of basis choice on pricing accuracy.

---

### 3. 🔬 Longstaff-Schwartz with Neural Network — `Longstaff-Schwartz_NeuralNetwork_Option_Pricing.ipynb`

This notebook extends the **Longstaff-Schwartz** algorithm (LSM) by replacing regression on basis functions with a neural network.

🧠 Key Contributions:
- Neural networks approximate continuation values.
- Better capture of non-linear payoff structures.
- Works well in high-dimensional state spaces.

📦 Includes:
- Custom PyTorch model.
- Per-time-step training loop.
- Confidence interval estimation.

---


### 4. 🤖 Deep Hedging — `Deep Hedging.ipynb`

Inspired by the paper *Deep Hedging (Buehler et al.)*, this notebook trains a neural network to **replicate and hedge options** under **transaction costs**.

🚀 Highlights:
- End-to-end hedging policy learned via PnL optimization.
- Handles multi-asset and frictional markets.
- Visual analysis of hedging strategies.

🎯 Why it matters:
- No need for explicit greeks or analytic solutions.
- Scalable to high dimensions and realistic frictions.

---

## 🧰 Requirements

To run the notebooks, you need:

- Python ≥ 3.8
- `numpy`, `matplotlib`, `scipy`
- `torch` (for notebooks using neural networks)
- `tqdm`, `seaborn` (for visualization and progress tracking)

```bash
pip install numpy matplotlib scipy torch tqdm seaborn


## 🧰 Requirements

To run the notebooks, you need:

- Python ≥ 3.8
- `numpy`, `matplotlib`, `scipy`
- `torch` (for notebooks using neural networks)
- `tqdm`, `seaborn` (for visualization and progress tracking)

```bash
pip install numpy matplotlib scipy torch tqdm seaborn
```

---

## 👤 Author

👨‍💻 Guillaume Routier  
🎓 MSc Probabilité & Finance – École Polytechnique & Sorbonne Université  
📬 [Contact me on LinkedIn](https://www.linkedin.com/in/guillaume-routier/)

---

## 📌 Disclaimer

These notebooks are for educational and demonstrative purposes only. They do not constitute financial advice.

---

## ⭐ If you find this useful...

Feel free to **star** the repo or get in touch for collaboration!
