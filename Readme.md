Try the code online: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/dkozel/JupyterNotebookTemplate/main?labpath=Matplotlib%20Examples.ipynb)

## Local Setup Instructions

Install [Visual Studio Code](https://code.visualstudio.com/)

Install VS Code Extensions
* [Jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter)

Setup Python environment

You can either use Conda or venv. Keysight's Python modules for working with ADS Pathwave datastore files require very specific versions of Python and some dependencies.


### For venv
```
pip install -r requirements.txt
```

### For Conda
Install Conda, I suggest miniconda.

```
conda env create -f environment.yml
```