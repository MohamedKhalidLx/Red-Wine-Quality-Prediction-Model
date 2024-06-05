# Wine Quality Prediction

![Python](https://img.shields.io/badge/Python-3.7%2B-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green)

This GitHub project aims to develop a machine learning model for predicting the quality of wine using Python. The project is a collaborative effort between two team members, Adham, Ziad and me, who have worked together to create an accurate and reliable wine quality prediction system.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Dependencies](#dependencies)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [Contact](#contact)
- [License](#license)

## Introduction

Wine quality prediction is an important task in the winemaking industry. By analyzing various chemical properties of wine samples, it is possible to estimate their quality. In this project, we have employed machine learning techniques to build a model that can predict the quality of wine based on its chemical attributes.

The goal of this project is to provide winemakers and enthusiasts with a reliable tool to assess the quality of their wines. By using this model, users can input the chemical composition of a wine sample and obtain a predicted quality rating. This can be particularly useful in quality control, wine production, and decision-making processes.

## Dataset

We have used the "Wine Quality" dataset, which is freely available on the UCI Machine Learning Repository. The dataset consists of various physicochemical properties of red and white wines, along with their corresponding quality ratings provided by experts. The dataset has been preprocessed and cleaned to ensure accurate results.

For more information about the dataset, please refer to the following publication:

- P. Cortez, A. Cerdeira, F. Almeida, T. Matos, and J. Reis. "Modeling wine preferences by data mining from physicochemical properties." Decision Support Systems, Elsevier, 47(4):547-553, 2009.

## Dependencies

The following dependencies are required to run the project:

- Python 3.7 or higher
- pandas
- numpy
- matplotlib
- seaborn
- plotly
- scikit-learn
- termcolor

You can install these dependencies by running the following command:

```
pip install -r requirements.txt
```

## Installation

To get started with the project, you can follow these steps:

1. Clone the repository:

```shell
git clone https://github.com/MohamedKhalidLx/Wine-Quality-Prediction.git
```

2. Change to the project directory:

```shell
cd Wine-Quality-Prediction
```

3. Install the required dependencies as mentioned in the [Dependencies](#dependencies) section.

## Usage

To use the wine quality prediction model, you can follow these steps:

1. Ensure that you have the necessary dependencies installed.

2. Prepare your dataset or use the provided "winequality.csv" file.

3. Open the Jupyter Notebook or Python script where the model is implemented.

4. Run the code and provide the necessary inputs (chemical attributes of the wine).

5. Obtain the predicted quality rating for the wine sample.

## Results

After training the model on the wine quality dataset, we achieved promising results. The accuracy of the model is approximately 85%, indicating its ability to accurately predict the quality of wines. However, it is important to note that the model's predictions are based on the provided dataset, and the accuracy may vary for different wine samples.

For more detailed information about the results and analysis, please refer to the [Results](/results) directory.

## Contributing

We welcome

 contributions to improve this project. If you have any ideas, suggestions, or bug fixes, please open an issue or submit a pull request. Your contributions will be acknowledged and greatly appreciated.

## Contact

Name: Mohamed Khaled Mahmoud Sayed  
E-mail: Mo7ammad244@gmail.com

## License

This project is licensed under the [LICENSE](LICENSE). Feel free to use and modify the code as per your requirements.
