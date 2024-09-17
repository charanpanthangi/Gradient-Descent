### `README.md`

```markdown
# Gradient Boosting Model Repository

This repository demonstrates the use of Gradient Boosting for both classification and regression tasks. It includes code for univariate and bivariate analysis, model training, evaluation, saving, and loading.

## Table of Contents
- [Overview](#overview)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Dataset](#dataset)
- [Analysis](#analysis)
- [Model Training and Evaluation](#model-training-and-evaluation)
- [Model Saving and Loading](#model-saving-and-loading)
- [Usage](#usage)
- [License](#license)

## Overview
This project demonstrates:
- **Univariate Analysis**: Visualizes the distribution of each feature.
- **Bivariate Analysis**: Shows relationships between features.
- **Gradient Boosting Classification**: Trains and evaluates a Gradient Boosting classifier.
- **Gradient Boosting Regression**: Trains and evaluates a Gradient Boosting regressor.
- **Model Saving and Loading**: Saves and loads models using `.pkl` files.

## Prerequisites
- Python 3.x
- Required Python libraries:
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `seaborn`
  - `matplotlib`
  - `pickle`

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/gradient-boosting-model.git
   ```
2. Navigate to the project directory:
   ```bash
   cd gradient-boosting-model
   ```
3. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Dataset
Replace `'your_data.csv'` with the path to your dataset file. Ensure it includes features and target columns appropriate for classification and regression tasks.

### Example dataset structure:
- For classification: `class_target`
- For regression: `reg_target`

## Analysis
- **Univariate Analysis**: Histograms are plotted for each feature.
- **Bivariate Analysis**: Pair plots visualize relationships between features.

## Model Training and Evaluation
1. **Classification**: Trains a Gradient Boosting classifier and evaluates its performance.
2. **Regression**: Trains a Gradient Boosting regressor and evaluates its performance.

## Model Saving and Loading
- **Saving**: Models are saved as `gb_classifier.pkl` and `gb_regressor.pkl`.
- **Loading**: Models can be loaded and used for predictions with new data.

## Usage
1. Replace `'your_data.csv'` with your dataset file path in the script.
2. Run the Python script to perform analysis, train models, and save them:
   ```bash
   python gradient_boosting_model.py
   ```
3. To make predictions with new input data, use the provided functions to load the model and pass new data.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```

### `requirements.txt`

```plaintext


### Explanation:
- **`README.md`**: Provides an overview of the project, installation instructions, dataset information, and how to use the code.
- **`requirements.txt`**: Lists the required Python libraries and their versions.

Replace placeholders like `yourusername` and `your_data.csv` with your actual repository name and dataset file path.
