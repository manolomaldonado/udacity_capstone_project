# Udacity Machine Learning Engineer Nanodegree: Capstone Project

*Applied machine learning for temporomandibular disorders diagnosis*

## Project Instructions

1. Clone the repository and navigate to the downloaded folder.

```
git clone https://github.com/manolomaldonado/udacity_capstone_project
cd udacity_capstone_project
```

2. Create and activate a new environment. We are going to use python 3.7 and install numpy, pandas, keras, matplotlib and scikit-learn packages.

```
conda create -n ucp python=3.7 matplotlib numpy pandas keras scikit-learn
source activate ucp
```

** Optional: ** It's is possible to create the required environment by using the provided `ucp.yml` file. To do it so, run the following command instead:

```
conda env create -f ucp.yml
```


1. Create an [IPython kernel](http://ipython.readthedocs.io/en/stable/install/kernel_install.html) for the `ucp` environment. 

```
conda install ipykernel
python -m ipykernel install --user --name ucp --display-name "ucp"
```


4. Open the notebook.
```
jupyter notebook project.ipynb
```

5. Before running code, change the kernel to match the `ucp` environment by using the drop-down menu (**Kernel > Change kernel > ucp**). Then, follow the instructions in the notebook.


6. A complete list of packages needed to run your project is provided in the `requirements.txt` file in the repository.