# DataWhys Content Notebooks - NLP

> [!NOTE]  
> These notebooks have slight incompatibilities with [our latest blocks extention](https://github.com/aolney/jupyterlab-blockly-polyglot-extension): blocks may not render correctly when you click on solutions. However you should be able to solve all problems with the new extension.

This repository contains **special topic notebooks on NLP** for DataWhys in the form of JupyterLab notebooks (.ipynb files).

These notebooks are completely portable to all JupyterLab environments but require the Blockly extension for the full user experience (see prerequisites below).

For a complete list of topics covered, see [the course outline](Course-outline.ipynb).
Each topic has an introduction/worked example notebook and an independent problem solving notebook (`-PS`).

All materials are currently in Python.

The pedagogy assumes that students have already completed the **core topics** in [datawhys-content-notebooks](https://github.com/memphis-iis/datawhys-content-notebooks).

If that is not the case, we suggest students complete **at least** the first 11 topics of the core course before proceeding:

- Getting around
    - Getting around
- Data science and the nature of data
    - Data-science-and-the-nature-of-data.ipynb
    - Data-science-and-the-nature-of-data-PS.ipynb
- Plotting
    - Plotting.ipynb
    - Plotting-PS.ipynb
- Descriptive stats
    - Descriptive-statistics.ipynb
    - Descriptive-statistics-PS.ipynb
- Measures of association
    - Measures-of-association.ipynb
    - Measures-of-association-PS.ipynb
- Clustering
    - Clustering.ipynb
    - Clustering-PS.ipynb
- KNN classification
    - KNN-classification.ipynb
    - KNN-classification-PS.ipynb
- KNN regression
    - KNN-regression.ipynb
    - KNN-regression-PS.ipynb
- Simple linear regression
    - Simple-linear-regression.ipynb
    - Simple-linear-regression-PS.ipynb
- Multiple linear regression
    - Multiple-linear-regression.ipynb
    - Multiple-linear-regression-PS.ipynb
- Logistic regression
    - Logistic-regression.ipynb
    - Logistic-regression-PS.ipynb
    
Although these core topics will provide most of the general background needed, students may still need to refer to other core notebooks to understand specific models, e.g. random forests.

## Check it out!

### Static viewing

Click on any notebook in the repository, and GitHub will render it in your browser as a non-interactive document.

### Interactive viewing

Launch a demo session by clicking on the Binder badge below.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/memphis-iis/datawhys-content-notebooks-nlp/master?urlpath=lab)

If you've never used Jupyter or want to try the Blockly extension, check out the tutorial video below.

[![Tutorial video using Blockly](https://img.youtube.com/vi/-luPzplPDI0/0.jpg)](https://youtu.be/-luPzplPDI0 "Tutorial video using Blockly")


## Development

### Prerequisites

- [JupyterLab](https://jupyter.org/install)
- [Blockly extension](https://github.com/aolney/fable-jupyterlab-blockly-extension) (optional but strongly recommended)
- [Xeus Python Kernel](https://github.com/jupyter-xeus/xeus-python) (optional but strongly recommended)

The above is a minimal environment.
See the `binder` subfolder for the recommended [conda env](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#creating-an-environment-from-an-environment-yml-file) and [JupyterLab extension](https://jupyterlab.readthedocs.io/en/stable/user/extensions.html#using-the-terminal) installation.

### Internal development

Any other content-related materials, e.g. spreadsheets, should be placed [in the OneDrive folder](https://livememphis-my.sharepoint.com/:f:/r/personal/aolney_memphis_edu/Documents/DataWhys/content-planning?csf=1&e=LPEGbr). If you create an issue that references a document in that folder, please try to link to said document.

## Contributing

If you want to change/correct content, either create an issue describing your change or [use a `git` workflow to make the change](https://www.atlassian.com/git/tutorials/making-a-pull-request).
