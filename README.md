# XGlab

Softmax classifier experiments and notes.

Contents
- `softmax_mnist.ipynb` — notebook implementing a softmax classifier on MNIST with NumPy.
- `softmax_usps.ipynb` — notebook implementing a softmax classifier on USPS with NumPy.

Quick start
1. Create and activate a Python environment (recommended):

```bash
python -m venv .venv
source .venv/bin/activate    # macOS / Linux
.\.venv\Scripts\activate   # Windows PowerShell
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Open the notebook in Jupyter or run the script.

Notes
- The notebook uses full/mini-batch NumPy training; consider switching to PyTorch for GPU training and more features.
- See `.gitignore` for files excluded from the repo.
