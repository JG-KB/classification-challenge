# Spam Detector

This project uses two machine learning models, Logistic Regression and Random Forest Classifier, to classify whether an email is spam or not.

## Dataset
The dataset is sourced from the [UCI Machine Learning Library](https://archive.ics.uci.edu/dataset/94/spambase) and contains various features related to email content. The target column (`spam`) indicates whether an email is spam (`1`) or not (`0`).

## Steps
1. **Data Retrieval**: Imported data using Pandas from an online source.
2. **Data Preparation**:
   - Split data into features (`X`) and target (`y`).
   - Checked the balance of target labels.
   - Split into training (80%) and testing (20%) subsets.
   - Scaled features using `StandardScaler`.
3. **Model Training**:
   - Trained a Logistic Regression model.
   - Trained a Random Forest Classifier model.
4. **Model Evaluation**:
   - Calculated accuracy scores for both models.
   - Compared performance to determine which model was better.

## Results
- **Logistic Regression**: Struggled due to non-linear data relationships.
- **Random Forest Classifier**: Performed better due to its ability to handle complex data.

## Future Work
- Experiment with hyperparameter tuning.
- Explore additional metrics like Precision, Recall, and F1-Score.
- Investigate feature importance from the Random Forest model.

## Requirements
- Python 3.x
- Libraries:
  - `pandas`
  - `sklearn`

## Running the Code
1. Clone the repository.
2. Run the notebook file in a Jupyter Notebook environment.

## Author
This project was developed by a Machine Learning enthusiast to explore classification techniques.

