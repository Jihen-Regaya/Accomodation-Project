# Accommodation-Project

## Overview
This repository contains the code and resources for a project focused on clustering hotel names and their duplicates. The project demonstrates how to use text data and agglomerative clustering to group similar hotel names together, providing insights into potential duplicates and variants.

## Table of Context
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usgae)
  - [Preprocessing](#preprocessing)
  - [Agglomerative Clustering](#agglomerative-clustering)
  - [Evaluating Results](#exporting-results)
- [Results](#results)

## Getting Started

### Prerequisites
- Python (3.6 or higher)
- Required Python packages: numpy, pandas, sci-kit-learn  
### Installation
1- Create a virtual environment (recommended)
2- Install the required packages


## Usage

### Preprocessing
1- Cleaning data
2- Tokenization
3- Deleting stop words
4- TF-IDF
### Agglomerative Clustering
Hierarchical clustering is the best clustering technique to use for this project since the number of clusters is hard to predict at first 
### Evaluating Results
A methodical way of evaluating the results, I exported hotel names and their duplicates in a CSV file which looks more organized and clear.

## Results
After running the provided scripts, you will find the following files:

`clustered_data.csv`: Contains clustered data with each row representing a cluster and its corresponding data points.
`unique_hotel_names.csv`: Contains a list of unique hotel names extracted from the clustered data.
