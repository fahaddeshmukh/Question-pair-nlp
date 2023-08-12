# Semantic Duplicate Detection: Quora Question Pairs Analysis using Machine Learning

This repository contains files for a machine learning (ML)-based solution to the Quora Question Pairs problem, hosted on Kaggle. This challenge falls within the scope of natural language processing (NLP) and involves the task of identifying whether pairs of questions from the Quora platform are duplicates.

## Directories

The project is structured as follows:

- **bin**: This directory contains the source code files required to run the analysis.
 - `quora.ipynb`: This Jupyter Notebook file provides an alternative interface for running the analysis interactively. It contains the same code as `src.py` but provides easy accessablity along with a narrative.

- **data**: This directory contains the dataset used for the analysis.
  - `train.csv`: The CSV file that contains the original dataset, that contains questions. This file is required for running the analysis. Please ensure that it is located in this directory.

- **docs**: This directory contains any documentation related to the project.
- **plots**: This directory contains the EDA plots used for the analysis.
## Installation

To use this script, you need to have Python installed on your system (3.8 or higher). You also need to install the required dependencies by running the following command:

```
pip install -r requirements.txt
```

## Requirements

The script requires the following Python packages:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- lightgbm
- spacy
- FuzzyWuzzy

You can install these packages by running the command mentioned in the "Installation" section.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE.md) file for details.

## Citation Information

Citation information for this project can be found in the Citation files in the directory.
URL for Citations: https://github.com/fahaddeshmukh/Causes-of-death-analysis/blob/main/CITATION.cff
## Contact Information
For any questions, suggestions, or issues, please feel free to contact:

- Name: Fahad Deshmukh
- Email: deshmukh@uni-potsdam.de
