# Fake News Detection

This project is a **Fake News Detection** system using Python. The goal is to classify news as **real** or **fake** using machine learning techniques.

## Project Files

- `FakeNewsDetection.ipynb` – Jupyter Notebook containing the full code for data preprocessing, model training, and evaluation.
- `train.csv` – Training dataset.
- `test.csv` – Test dataset.
- `sample_submission.csv` – Sample submission format for predictions.

## Features

- Text preprocessing (removing punctuation, stopwords, etc.)
- Feature extraction using TF-IDF
- Machine Learning models for classification (e.g., Logistic Regression, Random Forest)
- Model evaluation with accuracy metrics

## Installation

1. Clone the repository:

```bash
git clone https://github.com/tasnia-cse50/Fake-News-Detection.git
````

2. Install required Python packages:

```bash
pip install -r requirements.txt
```

*(If you don’t have `requirements.txt`, install packages like pandas, scikit-learn, numpy, matplotlib, and nltk.)*

## Usage

1. Open the Jupyter Notebook:

```bash
jupyter notebook FakeNewsDetection.ipynb
```

2. Follow the notebook cells to:

   * Load the dataset
   * Preprocess the text
   * Train and evaluate models
   * Make predictions on new data

## Contributing

Feel free to fork this repository, improve the model, or add new features.

## License

This project is open source and available under the MIT License.

```
