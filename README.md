# Graph Neural Network Recommendation Engine

A notebook-based project exploring graph neural networks for recommendation.

The project is organized around a Jupyter notebook, providing a starting point for exploring graph-based recommendation and experimenting with the implementation.

## Getting started

### Run in Google Colab

[Open the notebook in Google Colab](https://colab.research.google.com/drive/1rplKqpKEOscBSbkyggkmwbf_yT_0y4ki)

Use the existing Colab notebook to explore the project without cloning the repository.

Alternatively, [open the GitHub-hosted notebook in Colab](https://colab.research.google.com/github/hrczggyrgy/graph_NN_reco_engine/blob/main/graph-nn_.ipynb) to work from the version stored in this repository.

### Run locally

Clone the repository:

```bash
git clone [https://github.com/hrczggyrgy/graph_NN_reco_engine.git](https://github.com/hrczggyrgy/graph_NN_reco_engine.git)
cd graph_NN_reco_engine
```

Create and activate a virtual environment:

```bash
python -m venv .venv
```

On macOS or Linux:

```bash
source .venv/bin/activate
```

On Windows PowerShell:

```powershell
.\.venv\Scripts\Activate.ps1
```

Install and launch JupyterLab:

```bash
python -m pip install --upgrade pip
python -m pip install jupyterlab
jupyter lab
```

Open `graph-nn_.ipynb` and review its setup and data-loading cells before running the notebook. Install any additional dependencies required by those cells, and adjust environment-specific paths where necessary.

> Installing JupyterLab provides the notebook interface; it does not install the project's model or data-processing dependencies.

## Repository structure

```text
graph_NN_reco_engine/
├── README.md          # Project overview and getting-started guide
└── graph-nn_.ipynb     # Main project notebook
```

## Reproducibility

Before running experiments, check the notebook for:

- Required libraries and package versions.
- Dataset sources, download instructions, and file paths.
- Runtime requirements and hardware-specific settings.
- Random seeds and experiment configuration.

The repository does not currently include a separate dependency manifest. Consult the notebook for its environment setup.

## Project scope

This repository presents the project in notebook form. It does not currently include a standalone application, serving API, or packaged installation workflow.
