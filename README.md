
# WeRateDogs : A Data Wrangling Project

## by Chukwunonso Emmanuel Chukwumaeze

## Objectives

This is a repository for Udacity Data Analyst Project 2 (Data Wrangling). The dataset used in the project is also included in this repository.

## Introduction

I gathered data using three different methods in this project;
1. Using pandas read_csv
2. Using Requests library to gather image predictions data
3. Tweepy library to gather additional data via Twitter API
The three datasets were assessed and cleaned individually, then later merged as one.

## Project Methodology

The main steps for this project can be summarized as follows:

- Data Wrangling
  - Data Gathering
  - Data Assessment
  - Data Cleaning
- Analysis/Visualization


## How to Navigate:
> * The notebook __wrangle_report.ipynb__ details my thought processes as I proceed for on the process of wrangling the datasets. It details every reason for the cleaning I chose to do
> * The notebook __wrangle_act.ipynb__ contains the code of the actual process of the wrangling, with code comments and markdown cells to track the logical process of the steps taken.
> * The notebook __act_report.ipynb__ contains the insights derived from Exploratory Data Analysis of the dataset __after wrangling__

## Requirements
The required packages have been added via two files:
  * __environment.yaml__ - this file is for the **conda environment** if you want to add just run this code in your anaconda prompt when you've entered into the root folder
  ```conda env create -f environment.yaml```
  * __requirements.txt__ - this file is for using __just Python__ instead of Anaconda, to add the environments, run this code in the root folder in your python environment
  ```pip3 install -r requirements.txt```
