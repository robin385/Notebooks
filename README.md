
# Kaggle Notebooks Collection

A curated collection of Jupyter notebooks for various Kaggle competitions, experiments, and tutorials. These notebooks demonstrate end-to-end workflows—data loading, preprocessing, model training, evaluation, and submission—using PyTorch and Hugging Face Transformers.

---


## 🚀 Quickstart

1. **Clone the repo**  
   ```bash
   git clone https://github.com/yourusername/kaggle-notebooks.git
   cd kaggle-notebooks


2. **Create a virtual environment**

   ```bash
   python3 -m venv .venv
   source .venv/bin/activate       # on Windows: .venv\Scripts\activate
   ```

3. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Launch Jupyter Lab / Notebook**

   ```bash
   jupyter lab
   ```

   or

   ```bash
   jupyter notebook
   ```

5. **Open any notebook** under the `notebooks/` directory and run cell-by-cell.

---

## 📦 Core Dependencies

* [Python 3.8+](https://www.python.org/downloads/)
* [PyTorch](https://pytorch.org/)
* [Transformers (Hugging Face)](https://github.com/huggingface/transformers)
* [pandas](https://pandas.pydata.org/)
* [scikit-learn](https://scikit-learn.org/)
* [Matplotlib](https://matplotlib.org/) / [Seaborn](https://seaborn.pydata.org/) (for visualization)

All required packages are listed in `requirements.txt`:

```text
torch>=1.12
transformers>=4.18
pandas>=1.3
scikit-learn>=1.0
matplotlib>=3.4
seaborn>=0.11
jupyterlab
tqdm
```

---

## 🗒️ Featured Notebooks

| Notebook                                     | Description                                         |
| -------------------------------------------- | --------------------------------------------------- |
| `BirdClef2025`          | wildlife classificaiton by sound |
| `DashCam`      | Collision Detection from dashcam footage   |
---

## 🔧 Usage Tips

* **Reproducibility**: Set a fixed random seed at the top of each notebook.
* **Fast experimentation**: Use a subset of data (`head()`) or reduce epochs.
* **GPU support**: Ensure `torch.cuda.is_available()` and move models/data to `.to(device)`.
* **Caching & checkpoints**: Save model checkpoints to speed up iterative tuning.


