# How Long Does It Take To Cook This? 

*Project II of COMP30027 (Machine Learning) - The University of Melbourne*

Author: 
* Tuan Khoi Nguyen - `1025294`
* Hai Hong Tran - `1012919`

## About
This repo includes all of processed files that were used in the Project. The main aim of the Project is to successfully predict cooking durations for culinary recipes from *food.com*. Our implementation strategy has helped us to reach the top position on the cohort's [Kaggle Competition](https://www.kaggle.com/c/comp30027-2021/leaderboard), which consists of 400 teams from the whole course, leaving the 2nd (*) highest team 1% behind (70 correct guesses).

(*): It is actually the 3rd place on the Kaggle leaderboard, since our 2 accounts both ended up on top.

## Files
Submission file of this project includes the following files:

### `Report.pdf`

The report file for this project, consisting of analysis and method description.

### `input` folder

The folder is located inside `COMP30027_2021_Project2_datasets` folder. The folder stores two files containing featured engineered dataset, `train_seconds.csv` and `test_seconds.csv`.

### `output` folder

The folder includes all `.csv` output files which have been submitted to Kaggle for testing.

### `COMP30027-Project-2.ipynb`

This is the main file which implements the following task:
    1. Data Preprocessing: contains insightful data visualisation and preprocessing for later use
    2. Feature evaluation and selection: contains model training on different features to identify most correlated feature and explains the choice of feature selection
    3. Feature engineering: contains how new feature is engineered
    4. Model Evaluation: contains every model training and prediction generation

Running instructions:
* Requires the input dataset to run, which is not included in the `.zip` file due to sizing.
* For each section, the code must be run sequentially, so that all necessary functions are defined, and all data are imported. These cells are always defined at the beginning of every section.
* Don't forget to import or install the necessary libraries before proceeding. See first cell for list of libraries.

In order to run each training model, please run every code snippet in section 1 (Data Preprocessing), which contains functions used in creating new feature and section 3 (Feature Engineering). Then move on to section 4 (Model Evaluation) to run code there, where each part in the section has been labelled clearly explaining the type of model used and set of input features.

### `COMP30027-Project-2-Feature-Selection.ipynb`
   
This file produces code for Feature Selection part. The output of this file are training results for different Top Percentile Feature Selection, as well as a comparison plot.

Also requires the same input files as the main file `COMP30027-Project-2.ipynb`. In order to run feaure evaluation model here, please run the library import and helper function snippets first. Each snippet is put at the top of the file, labelled carefully and can be run separately. Final snippet contains result from the above model evaluation and plotting.