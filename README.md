# openeo-local

openEO local client-side processing

## Developer Environment

The openeo packages seem to expect python `3.9`.

Therefore a vscode devcontainer is provided at `./.devcontainer/devcontainer.json` - which can be activated within vscode.

## Setup

Create a virtual environment

```bash
python -m venv venv
source ./venv/bin/activate
python -m pip install -U pip
```

Install required packages

```bash
pip install -U -r requirements.txt
```

## Run notebook

Open the notebook in the Jupyter Lab server

```bash
jupyter lab --LabApp.default_url=/lab/tree/client_side_processing.ipynb
```

Run all the cells
