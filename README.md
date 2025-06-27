# CSID Project1: Multi-Output Regression Analysis

A machine learning project implementing an enhanced multi-output regression pipeline using scikit-learn. The project focuses on predicting two target variables ('QV2M_x' and 'ACTUAL (MM)') using a sophisticated feature engineering and selection approach.

## Table of Contents

1. [Overview](#overview)
2. [Features](#features)
3. [Requirements](#requirements)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Technical Details](#technical-details)
7. [Performance](#performance)
8. [Contributing](#contributing)
9. [License](#license)

## Overview

This project demonstrates a robust implementation of multi-output regression using scikit-learn's Pipeline architecture. The implementation includes advanced feature engineering techniques such as PCA dimensionality reduction and feature selection using f-regression scores.

## Features

* Multi-output regression pipeline
* Feature engineering with PCA (95% variance retention)
* Feature selection using f-regression
* Hyperparameter optimization with GridSearchCV
* Cross-validation with 10 folds
* Parallel processing support

## Requirements

* Python 3.x
* scikit-learn
* numpy
* pandas

## Installation

```bash
# Clone the repository
git clone https://github.com/wrickguha/CSID_Project1.git

# Install required packages
pip install -r requirements.txt
```

## Usage

The project implements a complete machine learning pipeline that can be used for multi-output regression tasks. The pipeline includes:

1. Data preprocessing with StandardScaler
2. Dimensionality reduction using PCA
3. Feature selection using f-regression
4. Multi-output regression using ElasticNet

## Technical Details

The implementation uses several advanced techniques:

* PCA with 95% variance retention for dimensionality reduction
* SelectKBest with f-regression for feature selection
* MultiOutputRegressor for handling multiple targets
* GridSearchCV with 10-fold cross-validation for hyperparameter tuning
* Parallel processing with n_jobs=-1 for improved performance

## Performance

The model achieves high accuracy through:
* Comprehensive hyperparameter tuning
* Robust feature selection
* Efficient dimensionality reduction
* Cross-validation for reliable performance estimation

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a feature branch
3. Implement your changes
4. Add appropriate tests
5. Submit a pull request

## License

This project is licensed under the MIT License - see [LICENSE](LICENSE) for details.
