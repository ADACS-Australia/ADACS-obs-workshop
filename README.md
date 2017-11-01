# ADACS-obs-workshop
Repo to collect material for the ADACS intro to computation for astronomorer's workshop


## Day 1

1. Opening remarks/keynote
    1. Astronomer's toolkit
2. Version Control with git and github
    1. global config
    2. Create and commit to a repository
    3. explore history
    4. check out older versions
    5. collaboration/ pull requests
    6. branching
3. Good coding practices (in Python)
    1. Jupyter Notebooks
    2. Intro to Python
        1. code layout
        2. commenting
        3. packages
        4. Python syntax and data types
    3. Visualisation - The good and the bad

## Day 2

1. Working with pandas DataFrames in python
    1. Loading and exploring data
    2. Merging data
    3. Cleaning data
2. Plotting data
    1. matplotlib
    2. seaborn
3. Astronomy examples with AstroPy
    1. Overview 
    2. Working with FITS files and WCS
    3. Using Coorindates
    4. Radio astronomy related tutorial(?) 
4. Virtual Observatories
    1. ASVO
    2. IVOA (specifically CDS services)
5. Data Acquisition (using Topcat, CDS tools and Python)
    1. Querying
    2. Visualisation


## Day 3

1. Introduction to ML
    1. Data preparation and exploratory data analysis (review from previous day)
    2. Classification
        1. Model evaluation
        2. Model tuning
        3. reporting
    3. Regression
    4. Clustering
    5. Dimensionality reduction
2. Introduction to Nimbus
3. Q&A session followed by sundowner



**Note**:
Tutorials build on each other and assume basic knowledge from previous days is carried forward (e.g., you know the basic data structures and operations and how to write a script/ run jupyter notebooks). 
Where possible training material will be uploaded as an ipython notebook and checked for python 2.7 and 3.X compatability.

## Downloading only the folder of the training you attended

If you want to download a specific folder (e.g. Day 1) instead of cloning the entire repository you can use svn to checkout a subdirectory of this repository by running the following command in your shell:

`svn checkout https://github.com/r-lange/ADACS-obs-workshop/trunk/Day1`

**Note**: you simply need to change the url of the folder by replacing `tree/master` with `trunk`


