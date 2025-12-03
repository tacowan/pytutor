# PyTutor

A Jupyter notebook project for learning and experimentation.

## Project Structure

```
pytutor/
├── notebooks/          # Jupyter notebooks
├── data/              # Data files
│   ├── raw/          # Raw, immutable data
│   └── processed/    # Cleaned, processed data
├── src/              # Source code for reusable modules
├── requirements.txt  # Project dependencies
└── README.md        # This file
```

## Setup Instructions

### 1. Create Virtual Environment

Create a Python virtual environment to isolate project dependencies:

```bash
python3 -m venv venv
```

### 2. Activate Virtual Environment

**On Linux/Mac:**
```bash
source venv/bin/activate
```

**On Windows:**
```bash
venv\Scripts\activate
```

### 3. Install Dependencies

Install Jupyter and other required packages:

```bash
pip install --upgrade pip
pip install -r requirements.txt
```

### 4. Start Jupyter

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Or launch JupyterLab (modern interface):

```bash
jupyter lab
```

Your browser should automatically open to the Jupyter interface. Navigate to the `notebooks/` directory to see the example notebook.

## Getting Started

1. Open `notebooks/getting_started.ipynb` to see a basic example
2. Create new notebooks in the `notebooks/` directory
3. Place raw data files in `data/raw/`
4. Save processed data in `data/processed/`
5. Create reusable Python modules in `src/`

## Deactivating the Virtual Environment

When you're done working:

```bash
deactivate
```

## Tips

- Always activate the virtual environment before working on the project
- Keep notebooks in the `notebooks/` directory
- Use meaningful names for your notebooks
- Add new dependencies to `requirements.txt`
- Don't commit large data files to git (they're already ignored)
