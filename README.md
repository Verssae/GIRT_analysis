# GitHub Issue Practices: An Empirical Study from Developers' Perspective

This repository contains the code and data for the paper "An Empirical Study on GitHub Issue Practices from the Perspective of Developers".

## Overview

This project explores GitHub Issue Report Templates (IRT) and the practices around their use in open-source projects. The study examines over 67,000 IRTs from 34,000 projects, analyzing their components and identifying common trends in how developers utilize these templates for bug reports, feature requests, and other issue types based on the [GIRT dataset(MSR'23)](https://github.com/kargaranamir/girt-data).

The study aims to provide insights into how IRTs are used in practice, highlighting the most important components developers tend to include in their issue reports.

## Files

- `data_analysis.ipynb`: The Jupyter notebook containing the code for data analysis and visualization.
- `GIRT/*.zip`: The dataset used in the study, containing 67,000+ IRTs from 34,000+ projects at the time of collection ([GIRT dataset](https://github.com/kargaranamir/girt-data)).

## Requirements

To run the analysis code, you'll need the following dependencies:

- Python 3.7+
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Results

The key findings from the study include:

- The majority of IRTs are used for bug reports and feature requests.
- Developers prioritize components like “Additional Context”, “Expected Behavior”, and “Steps to Reproduce” in bug reports.
- The use of GitHub’s default templates is common, but there is still significant room for customization based on project needs.

## License

The code in this repository is licensed under the [MIT License](./LICENSE). Additionally, the dataset used is provided under the MIT License by the authors of the GIRT dataset [girt-data/LICENSE](https://github.com/kargaranamir/girt-data/blob/main/LICENSE).
