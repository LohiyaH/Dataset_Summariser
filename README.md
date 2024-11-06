# Dataset Summarizer

This repository provides a Python-based summarizer tool to load, analyze, and visualize datasets using libraries like `pandas`, `numpy`, `matplotlib`,`seaborn`,`tensorflow`,`re`,`pickle`. This tool aims to give a quick statistical summary and visual insights into your data, making it easier to explore data patterns and distributions.

## Table of Contents
- [Description](#description)
- [Features](#features)
- [Libraries Used](#libraries-used)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Description

The Dataset Summarizer tool helps you quickly load a dataset, generate descriptive statistics, and visualize key patterns within the data. It handles tasks like summarizing each column's basic statistics, handling missing values, and generating histograms, box plots, and heatmaps to aid in data understanding.

## Features

- Load and display the first few rows of a dataset.
- Generate column-wise summary statistics (mean, median, mode, standard deviation).
- Handle missing values in the dataset.
- Visualize data distributions and relationships with plots like histograms, box plots, and heatmaps.

## Libraries Used

The following Python libraries were used in the project:

1. **pandas**
   - A data manipulation library used to load, transform, and summarize datasets.
   - Essential functions like `.head()`, `.describe()`, and `.info()` help to understand data structure and content.
   
2. **numpy**
   - A library for numerical operations, supporting statistical functions such as `mean`, `median`, and `std`.
   - Provides efficient ways to handle missing data and large numerical computations.

3. **matplotlib**
   - A foundational library for creating static and interactive visualizations.
   - Used to generate simple plots, like histograms and box plots, which help visualize data distribution.

4. **seaborn**
   - A high-level library built on `matplotlib` for creating attractive and informative statistical plots.
   - Used for advanced visualization types, such as pair plots and heatmaps, that facilitate data exploration and pattern discovery.

## Installation

To install the necessary libraries, run:
```bash
pip install pandas numpy matplotlib seaborn

# transformer-abstractive-summarization
Abstractive Text Summarization using Transformer

- Implementation of the state of the art Transformer Model from "Attention is all you need", Vaswani et. al.
  https://arxiv.org/abs/1706.03762

- Inshorts Dataset: https://www.kaggle.com/shashichander009/inshorts-news-data
