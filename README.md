# Applied Statistics

![python_logo](/images/logos/python_logo.png) ![jupyter_logo](/images/logos/jupyter_logo_mod_sh_title.png) ![markdown_logo](/images/logos/markdown_title.png) ![github_logo](/images/logos/github_logo_title.png) ![anaconda logo](/images/logos/anaconda_icon.resized.png) ![vsc logo](/images/logos/vsc_logo.resized.jpeg)

Author: Sean Humphreys

Email: <sean@cruaghgreen.com>

This repository contains the submissions for 2024 Applied Statistics module.

The Jupyter notebooks in this repository demonstrate statistical hypothesis testing, including testing for normality, t-Tests and ANOVA on various datasets.

The power of statistical tests, type I and type II errors are explored in the notebook.

## Prerequisites

Before running the Jupyter Notebooks in this repository, make sure you have the following installed:

- Github - GitHub is an online software development platform. It's used for storing, tracking, and collaborating on software projects.

- Anaconda - for managing Python environments and packages.

- Visual Studio Code - for editing and running Jupyter Notebooks.

- Python (via Anaconda).

## Installation Instructions


### Step 1 - Install Git ![github logo](/images/logos/github_logo_title.png)

To access the files in this repository Git Desktop must be installed on the local machine.

Git desktop installation files are accessed [here](https://desktop.github.com/).

Guides on the use of Git are available [here](https://docs.github.com/en/desktop/overview/getting-started-with-github-desktop).

This repository can be cloned with the following git command:

```bash
git clone https://github.com/humphs078/applied_statistics.git
```

### Step 2 - Install Anaconda ![anaconda logo](/images/logos/anaconda_icon.resized.png)

1. Go to the [Anaconda website](https://www.anaconda.com/products/individual) and download the latest version of Anaconda for your operating system (Windows, macOS, or Linux).

2. Follow the installation instructions on the website for your platform.

### Step 3 - Install Visual Studio Code ![vsc logo](/images/logos/vsc_logo.resized.jpeg)

If you don't have Visual Studio Code installed, download it from the [official website](https://code.visualstudio.com/).

Open VS Code and install the Jupyter extension:

+ Go to the Extensions view (Ctrl+Shift+X), search for "Jupyter", and click "Install"

### Step 4 - Open the Jupyter Notebook ![jupyter logo](/images/logos/jupyter_logo_mod_sh_title.png "jupyter logo")

1. Open the folder containing the repository in Visual Studio Code.

2. Navigate to the Jupyter notebook file (with the .ipynb extension).

3. Select the Python kernel (from the environment you created) by clicking the kernel name in the top-right corner of the notebook window.

### Step 5 - Run the Notebook

Once the environment and kernel are set up, you can start running cells in the Jupyter Notebook directly in Visual Studio Code. Simply press Shift + Enter to execute each cell.

This repository contains two Jupyter Notebooks:

- [Tasks Notebook](/tasks.ipynb)

- [Project Notebook](/project.ipynb)


## Python Dependencies![python logo](/images/logos/python_logo.png)

Once cloned the required python packages can be installed from the command line with the following command:

- with anaconda

```bash
conda install --yes --file requirements.txt
```

- or with pip

```bash
pip install -r requirements.txt
```
