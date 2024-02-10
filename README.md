# Matrix Analysis, spring semester 2023

This repository contains the notebooks for the exercises sessions of the course Matrix Theory

The course will address the following topics:
- Linear transformations
- Pseudo-inverse
- Projections and norms
- Eigenvalues, eigenvectors and eigenvalue problems
- Singular Value Decomposition
- Linear Equations
- Random matrices
- Linear Least Squares
- Linear differential and difference equations



### Local installation
For a local installation, you will need [git], [Python], and packages such as [numpy](https://numpy.org) or [Python scientific stack][scipy].
If you don't know how to install those on your platform, we recommend to install [Miniconda], a distribution of the [conda] package and environment manager.
Follow the below instructions to install it and create an environment for the course.

1. Download the Python 3.x installer for Windows, macOS, or Linux from <https://conda.io/miniconda.html> and install with default settings. For windows, it is advised to use the the Windows Subsystem for Linux (WSL) which allows you to run all Linux commands and applications within Windows. In order to use it, you need to install it first, e.g. for [Ubuntu](https://ubuntu.com/wsl) (but other Linux distributions are available as well). Once installed, open the Ubuntu WSL and proceed with Miniconda installation for Linux and create the environment.
   Skip this step if you have conda already installed.
   * macOS: double-click on `Miniconda3-latest-MacOSX-x86_64.pkg` or run `bash Miniconda3-latest-MacOSX-x86_64.sh` in a terminal.
   * Linux: run `bash Miniconda3-latest-Linux-x86_64.sh` in a terminal or use your package manager.
1. Open a terminal.
   Windows: open the Anaconda Prompt from the Start menu.
1. Install git with `conda install git`.
1. Navigate to the folder where you want to store the course material with `cd path/to/folder`.
1. Download this repository with `git clone https://github.com/epfl-lts2/matrix-theory-2023`.
1. Enter the repository with `cd matrix-theory-2023`.
1. Create an environment with the packages required for the course with `conda env create -f environment.yml`.
1. Run the steps below to start Jupyter. You should be able to run the [`test_install.ipynb`][test_install] notebook.

Every time you want to work, do the following:

1. Open a terminal. Windows: open the Anaconda Prompt from the Start menu.
1. Activate the environment with `conda activate matrix-theory-2023`.
1. Navigate to the folder where you stored the course material with `cd path/to/folder/matrix-analysis-2023`.
1. Start Jupyter with `jupyter lab`. The command should open a new tab in your web browser.
1. Edit and run the notebooks from your browser.
1. Once done, you can run `conda deactivate` to leave the `matrix-theory-2023` environment.


[git]: https://git-scm.com
[python]: https://www.python.org
[scipy]: https://www.scipy.org
[anaconda]: https://www.anaconda.com/download
[miniconda]: https://conda.io/miniconda.html
[conda]: https://conda.io
[conda-forge]: https://conda-forge.org
[test_install]: https://nbviewer.org/github/epfl-lts2/matrix-analysis-2023/blob/master/test_install.ipynb





