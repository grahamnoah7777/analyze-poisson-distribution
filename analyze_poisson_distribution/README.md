Poisson Distribution Analyzer

Overview

A Python-based statistical analysis tool that evaluates whether a dataset is consistent with a Poisson distribution. The program accepts  CSV files containing data sets, calculates degrees of freedom, chi-squared and reduced chi-squared, and p-value, generates a histogram plot to visually assess statistical distribution, and confirms or denies the data's fit to a Poisson distribution at a confidence level of p = 0.05.

Features

Imports CSV datasets.

Calculates and outputs DoF, chi-squared and reduced chi-squared, p-value.

Evaluates the consistency of observed data with a Poisson distribution at p = 0.05.

Generates graphical representations of the data.


Requirements

Python 3.x

numpy
scipy
matplotlib
pandas

Usage

Download or clone this repository.

Install the required dependencies.

Provide a CSV file containing the dataset.

Run analyze_poisson_distribution, call function with .csv file and specified column.

Project Structure

analyze_poisson_distribution.py — Main analysis program.

sample_poisson_data.csv — Example CSV dataset.