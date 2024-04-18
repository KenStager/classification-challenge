
# Spam Email Detection Using Machine Learning

## Project Overview

This project develops and compares two machine learning models, Logistic Regression and Random Forest Classifier, to detect spam emails. The models are trained and evaluated using a dataset obtained from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/94/spambase). The goal is to identify which model performs better in classifying emails as spam or not spam.

### Data Source

The spam email data can be downloaded from the following link:
- [Spam Data CSV](https://static.bc-edx.com/ai/ail-v-1-0/m13/challenge/spam-data.csv)

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

What you need to install the software and how to install them:

- Python 3.x
- Pandas library
- Scikit-learn library
- Joblib library (for model persistence)

### Installation

1. Clone the repository:
   ```bash
   git clone https://your-repository-url.git
   ```
2. Install required Python packages:
   ```bash
   pip install pandas scikit-learn joblib
   ```

## Usage

The main notebook `spam_detector.ipynb` demonstrates the following steps:

1. **Data Import and Display**: Load and display the dataset to ensure it's loaded properly.
2. **Data Splitting**: Split the data into training and testing sets.
3. **Feature Scaling**: Scale the feature data to normalize the distribution.
4. **Model Training**:
   - Train a Logistic Regression model.
   - Train a Random Forest Classifier model.
5. **Model Evaluation**:
   - Predict and evaluate both models using accuracy as the metric.
   - Compare the models based on their performance.
6. **Model Persistence**: Save and load the trained models using Joblib.

### Running the Notebook

Open and run the Jupyter Notebook for step-by-step execution:

```bash
jupyter notebook spam_detector.ipynb
```

## Model Performance

The project includes a detailed performance evaluation of the two models. Preliminary results suggest that Logistic Regression performed unexpectedly better than Random Forest in this specific scenario, although typical performance expectations might favor Random Forest.

## Contributing

Please read [CONTRIBUTING.md](https://your-repository-url/CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://your-repository-url/tags).

## Authors

- **Your Name** - *Initial work* - [YourUsername](https://github.com/YourUsername)

See also the list of [contributors](https://your-repository-url/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
