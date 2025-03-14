# Iris Flower Classification Project

## Overview
This project demonstrates the use of machine learning algorithms to classify Iris flower species based on their physical characteristics. It utilizes the classic Iris dataset and evaluates classification models such as K-Nearest Neighbors (KNN) and Gaussian Naive Bayes (NB).

## Dataset
- **Dataset Used:** Iris dataset (iris.csv)
- **Features:** Sepal Length, Sepal Width, Petal Length, Petal Width
- **Target Variable:** Species (Iris-setosa, Iris-versicolor, Iris-virginica)

## Project Structure
```
.
├── iris (1).csv           # Dataset file
├── iris_classification.py # Python script for analysis and modeling
├── README.md              # Project description
```

## Steps Included
1. **Data Exploration**
   - Viewing head, tail, summary statistics
   - Checking for null values

2. **Data Visualization**
   - Box plots
   - Histograms
   - Scatter matrix

3. **Model Training and Evaluation**
   - Data splitting (train-test split)
   - Cross-validation
   - Model comparison (KNN, Naive Bayes)

4. **Final Model Validation**
   - Accuracy metrics
   - Confusion matrix
   - Classification report

## Libraries Used
- `pandas`
- `matplotlib`
- `scikit-learn`

## Running the Project
1. Clone the repository:
```bash
git clone https://github.com/yourusername/your-repo.git
```

2. Install dependencies (if needed):
```bash
pip install pandas matplotlib scikit-learn
```

3. Execute the script:
```bash
python iris_classification.py
```

## Results
The K-Nearest Neighbors model achieved high accuracy in predicting the Iris species, making it suitable for reliable classification tasks.

## Author
- **Pavia Bera**
- **Contact:** paviabera@usf.edu

## License
This project is open-source under the [MIT License](LICENSE).

