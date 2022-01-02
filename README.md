

# Project assignment for Machine Learning & Statistics module 
*GMIT*
*December, 2021*


## Table of Contents

<!-- AUTO-GENERATED-CONTENT:START (TOC:collapse=true&collapseText="Click to expand") -->
<details>
<summary>"Click to expand"</summary>

- [About this repository](#about-this-repository)
    - [Goal](#goal)
    - [Files](#files)
- [How to download this repository](#how-to-download-this-repository)
- [How to run the code](#how-to-run-the-code)
- [References](#references)

</details>
<!-- AUTO-GENERATED-CONTENT:END -->

### About this repository
This document contains the Project assignment for 2021 Machine Learning & Statistics module at GMIT[1]. [See the instructions here.](https://github.com/ianmcloughlin/assessment-2122-machstat/blob/main/assessment.pdf)

#### Goal
The goal of this project is to help me become able to to discover patterns in real world data measurements, choose the appropriate models and functions of machine learning and make predictions based on often complex patterns to answer business questions, detect and analyse trends and help solve real-world problems. I will achieve this by exploring, understanding and demonstrating two Python[2] libraries, namely Scikit-Learn [3] and Scipy Stats [4], via Jupyter Notebooks [5]. 
In addition, Standards and guidelines for Quality Assurance at GMIT are strictly followed. [6] 

#### Files
In this repository you can find a few files. Main files for this assignment submission are two Jupyter Notebooks:

<img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" width=50 height=50 align="left">

- **scikit-learn.ipynb** - containing a demonstrations and visualisations of my three favorite algorithms available through scikit-learn Python library; 

<img src="https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.analyticsvidhya.com%2Fblog%2F2021%2F04%2Ftop-15-python-libraries-you-must-know-for-data-science-in-2021%2F&psig=AOvVaw2BEAUeic0dbkI8Na4tQpdj&ust=1641237435076000&source=images&cd=vfe&ved=0CAsQjRxqFwoTCMjpv4bkk_UCFQAAAAAdAAAAABAD" width=50 height=50 align="left">
- **scipy-stats.ipynb** - containing a demonstration and visualisation of a hypothesis testing using ANOVA, available through scipy-stats Python library; 
Structure of each notebook will be further explained in the below sections. Furthermore, file **requirements.txt** is required for interactive usage of the notebooks.



### How to download this repository
1. Go to my GitHub profile. [Click here.](https://github.com/vukasm)
2. Click the *Code*, then *Download ZIP* button at [this page](https://github.com/vukasm/MachineLearning-Statistics)
3. Run the code.


### How to run the code

1. Make sure you have Python installed. This is done best through Anaconda [7] package.
2. Make sure you have the following packages installed:
- Python (>=3.5)
- NumPy (>=1.11.0)
- SciPy (>=0.17.0)
- Joblib (>=0.11)
- Matplotlib (>=1.5.1)
- Pandas (>=0.18.0)

3. Anaconda [3] comes with `scikit-learn` by default, but, if needed it can be installed manually by typing `conda install scikit-learn` in a terminal. Check detailed instructions [here](https://scikit-learn.org/stable/install.html).
4. `SciPy` is part of the Anaconda distribution and can be installed with Anaconda by typing `conda install scipy` in a terminal. Otherwise detailed instructions can be found [here](https://scipy.org/install/).
5. Finally, you need to have Jupyter installed. Jupyter is also a part of anaconda package, but you can also install it by typing `conda install -c conda-forge jupyterlab` in a terminal or check [here](https://jupyter.org/install) for instructions.

6. Now that you have set your environment and have the repository downloaded, you need to launch `jupyter notebook` app.
- Click on spotlight, type terminal to open a terminal window.
- Enter the repository folder by typing cd /repository_name.
- Type `jupyter notebook` to launch the Jupyter Notebook App. The notebook interface will appear in a new browser window or tab.

8. Now you can execute the notebook:
- In the Notebook Dashboard navigate to find the notebook: clicking on its name will open it in a new browser tab.
- Click on the menu *Help -> User Interface Tour* for an overview of the Jupyter Notebook App user interface.
- You can run the notebook document step-by-step (one cell a time) by pressing shift + enter.
- You can run the whole notebook in a single step by clicking on the menu *Cell -> Run All*.
- To restart the kernel (i.e. the computational engine), click on the menu *Kernel -> Restart*. This can be useful to start over a computation from scratch (e.g. variables are deleted, open files are closed, etc…).

or alternative, run the jupyter notebook via **nbviewer** [8]:
[![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/vukasm/MachineLearning-Statistics/tree/main/)


- Open nbviewer: [Link to nbviewer](https://nbviewer.org/)
- Put URL of file in your repository in the textfield as shown. Press Go button to view the notebook.

Both these methods display notebook file as static html. For an interactive version it is fun to use **Binder** [9]:

[![binder](https://static.mybinder.org/badge.svg)](https://hub.gke2.mybinder.org/user/vukasm-machinel-ning-statistics-u7wte8uc/lab)


- In the nbviewer window you will see ‘Execute on Binder’ button. Click on it and you will see the notebook file opened exactly like you open it from local dashboard of notebook server on your local machine. You can perform all actions like add/edit cells, run the cells etc.



### **References** 

[1] GMIT. Galway-Mayo Institute of Technology. Available at: https://www.gmit.ie/
[2] Python Software Foundation. Welcome to python.org. Available at: https://www.python.org/  
[3] scikit-learn. Machine Learning in Python. Available at: https://scikit-learn.org/stable/
[4] Scipy - Scientific computing tools for Python. Available at: https://www.scipy.org/about.html
[5] Jupyter. Project Jupyter. Available at: https://jupyter.org/
[6] GMIT. Quality Assurance Framework. Available at: https://www.gmit.ie/general/quality-assurance-framework
[7] Anaconda. Installation. Available at: https://docs.anaconda.com/anaconda/install/index.html
[8] nbviewer. A simple way to share Jupyter Notebooks. Available at: https://nbviewer.org/
[9] Binder. Turn a Git repo into a collection of interactive notebooks. Available at: https://mybinder.org/

