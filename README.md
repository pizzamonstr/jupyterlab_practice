# jupyterlab_practice

A project repository for UBC dsci-toolbox assignment 7. It demonstrates JupyterLab features including cell types, markdown and LaTeX formatting, shell commands and magic commands in notebook cells, HTML export, and split tab layouts.

## Repository structure

* `question11.ipynb` contains a markdown heading, a Python function that comnputes the mean of a list, and a markdown cell explaining the code with the equation of the mean written in LaTeX
* `question12.ipynb` contains a shell command for displaying the working directory, a markdown cell showing the use of the `timeit` magic command, and the command used to export the notebook to HTML
* `question12.html` is the HTML export of `question12.ipynb`, generated without input code cells
* `question11-screenshot.png` and `question12-screenshot.png` are screenshots of the completed notebooks
* `environment.yaml` defines the computational environment

## Notebooks

The notebooks are independent and can be run in any order:

1. `question11.ipynb` demonstrates markdown headings, defining and calling a function, and LaTeX equation formatting
2. `question12.ipynb` demonstrates running shell commands in a cell with `!`, documenting the `%%timeit` cell magic, and exporting a notebook to HTML with `jupyter nbconvert`

## Environment

The computational environment is defined in `environment.yaml`. To recreate it:

```
conda env create -f environment.yaml
conda activate jupyter-practice
```

## License

This project is licensed under the MIT License. See `LICENSE` for details.