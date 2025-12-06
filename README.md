# Deep Learning Learning Repository

This repository contains implementations and experiments for learning deep learning concepts from scratch.

## Structure

```
DL_learning/
├── notebooks/          # Jupyter notebooks for experiments
├── requirements.txt    # Python dependencies
└── README.md          # This file
```

## Getting Started

### Setting up the Virtual Environment

This repository uses pyenv for Python version management. Follow these steps:

1. **Set the Python version** (if not already set):
   ```bash
   cd /Users/yuanyuan.chen/Desktop/DL_learning
   pyenv local 3.11.6  # or use the version specified in .python-version
   ```

2. **Create a virtual environment**:
   ```bash
   python -m venv venv
   ```

3. **Activate the virtual environment**:
   ```bash
   source venv/bin/activate
   ```

4. **Install dependencies**:
   ```bash
   pip install --upgrade pip
   pip install -r requirements.txt
   ```

5. **Start Jupyter**:
   ```bash
   jupyter notebook
   ```

### Quick Setup Script

Alternatively, you can run:
```bash
# Create and activate virtual environment
python -m venv venv
source venv/bin/activate

# Install dependencies
pip install --upgrade pip
pip install -r requirements.txt
```

### Deactivating the Virtual Environment

When you're done working:
```bash
deactivate
```

## Notebooks

- `mlp_backprop.ipynb`: Re-derive backpropagation for an MLP and implement a 2-3 layer MLP from scratch using NumPy. Includes visualization of activations and gradients.

