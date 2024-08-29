# BrainStation Data Science Capstone Template

This is a template repository for setting up your capstone project: it includes a simple folder structure and placeholder files for the most important assets you will be creating.

## Usage

1. Start a new GitHub repo using this template.
2. Update your `LICENSE` file with date and owner.
3. Update your `README.md` file to reflect the project - see a sample structure below and please refer to Synapse on what needs to be included here. 
4. Set up and activate your conda environment:
    - Create a new `conda` environment for your capstone project.
    - Activate the environment and export:
        ```bash
        conda env export > conda.yml
        ```
    - Make sure re-export every time after you update the environment.
    - You can reset your conda environment by running:
        ```bash
        conda env create -f conda.yml
        conda activate <your-env-name>
        ```
5. Add your own notebooks in `./notebooks/` and remove placeholders.
6. Add your own data in `./data/` and remove placeholder. Note: `.gitignore` will ignore the data folder when you push to github, save a copy of your raw and processed data, pickled models in a Google Drive folder and add the link in the `data_links.md` file.
7. Add your project documents, figures, reports, presentation pdf's in the `./docs` and remove placeholders.
8. Add your references (tutorials, papers, books etc.) in `./references`. 
9. Add your own scripts in `./src/` and remove unnecessary folders.

Feel free to rename the folder and customize the project structure to best fit your work - this template is just the starting point.

------------------------------------------------------------------------------

## Project Title
=========================

### Executive Summary

The Netflix Prize dataset is a large-scale dataset used to develop and evaluate movie recommendation algorithms, consisting of over 100 million ratings from nearly 500,000 users on 17,000 movies. 

The 1st goal is to observe preferences and ways to increase user engagement
The 2nd goal is to create a Recommendation system

### Demo

So far Data Processing and EDA Analysis is done. PLease check the EDA and Processing notebooks


### Methodology

Step 1) - Processed the data from next files 
Step 2) - Loaded them into Dataframes
Step 2)" Enhancements " - Since the dataSize is Huge. IN spte 2 planning to load the data into Database and prcess necessary ETL for ML Model
Step 3) - EDA analysis was done on the Movies, users and Rating Over the years of the Dataset
Step 4) - ML Model is yet to be determined and currently exploring the concepts on what can be used


### Organization

#### Repository 

Dataset :- https://www.kaggle.com/datasets/netflix-inc/netflix-prize-data

* `model`
    - `joblib` dump of final model(s)

* `notebooks`
    - contains all final notebooks involved in the project

* `docs`
    - contains final report, presentations which summarize the project

* `references`
    - contains papers / tutorials used in the project

* `src`
    - Contains the project source code (refactored from the notebooks)

* `.gitignore`
    - Part of Git, includes files and folders to be ignored by Git version control

* `conda.yml`
    - Conda environment specification

* `README.md`
    - Project landing page (this page)

* `LICENSE`
    - Project license

#### Dataset

Notebook folder Should contain the sample Pickle file

### Credits & References

https://en.wikipedia.org/wiki/Netflix_Prize
https://www.kaggle.com/datasets/netflix-inc/netflix-prize-data/data
