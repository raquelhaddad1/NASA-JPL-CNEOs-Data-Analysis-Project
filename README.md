[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/h_LXMCrc)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=12819585&assignment_repo_type=AssignmentRepo)
# DSCI 510 Final Project

## Name of the Project

Whew... That Was Close

## Team Members (Name and Student IDs)

Raquel Haddad 3452269703

## Instructions to create a conda environment

To create a virtual environment, run: ```conda create -n myenvironment python=3.10 -y```

To activate the conda environment, run: ```conda activate myenvironment```

## Instructions on how to install the required libraries

In your terminal, run: ```pip install -r requirements.txt```

## Instructions on how to download the data

Close-approach data from: https://ssd-api.jpl.nasa.gov/cad.api
Orbital elements for selected small-body IDs via: https://ssd-api.jpl.nasa.gov/sbdb.api

## Instructions on how to clean the data

After retrieving the raw API data, the script:
- Converts distance, diameter, velocity, and magnitude values to numeric format
- Filters and extracts relevant orbital elements
- Parses HTML news articles to extract titles, dates, and links

## Instrucions on how to run analysis code

Clone project repository and then run the main Python script. 

## Instructions on how to create visualizations

Refer to main Python script for 2D/3D plots.
