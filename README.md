# ADACS-obs-workshop
Repo to collect material for the ADACS intro to computation for astronomorer's workshop


## Day 1

1. Opening remarks/keynote
    a. Astronomer's toolkit
2. Version Control with git and github
    a. global config
    b. Create and commit to a repository
    c. explore history
    d. check out older versions
    e. collaboration/ pull requests
    f. branching
3. Good coding practices (in Python)
    a. Jupyter Notebooks
    b. Intro to Python
        i. code layout
        ii. commenting
        iii. packages
        iv. Python syntax and data types
    c. Visualisation - The good and the bad

## Day 2

1. Working with pandas DataFrames in python
    a. Loading and exploring data
    b. Merging data
    c. Cleaning data
2. Plotting data
    a. matplotlib
    b. seaborn
3. Astronomy examples with AstroPy
    a. Overview 
    b. Working with FITS files and WCS
    c. Using Coorindates
    d. Radio astronomy related tutorial(?) 
4. Virtual Observatories
    a. ASVO
    b. IVOA (specifically CDS services)
5. Data Acquisition (using Topcat, CDS tools and Python)
  a. Querying
  b. Visualisation


## Day 3

1. Introduction to ML
    a. Data preparation and exploratory data analysis (review from previous day)
    b. Classification
        i. Model evaluation
        ii. Model tuning
        iii. reporting
    c. Regression
    d. Clustering
    e. Dimensionality reduction
2. Introduction to Nimbus
3. Q&A session followed by sundowner



**Note**:
Tutorials build on each other and assume basic knowledge from previous days is carried forward (e.g., you know the basic data structures and operations and how to write a script/ run jupyter notebooks). 
Where possible training material will be uploaded as an ipython notebook and checked for python 2.7 and 3.X compatability.

## Downloading only the folder of the training you attended

If you want to download a specific folder (e.g. the Pawsey Roadshow files) instead of cloning the entire repository you can use svn to checkout a subdirectory of this repository by running the following command in your shell:

`svn checkout https://github.com/ADACS-Australia/Face-to-Face/trunk/Pawsey_Roadshow_MAR2017`

**Note**: you need to change the url of the folder by replacing tree/master with trunk


