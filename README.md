CUSTOMER RESPONSE PREDICTION USING DECISION TREE:

This project uses a Decision Tree Classifier to predict customer responses in a marketing campaign dataset. It includes preprocessing, training, evaluation, and a clear tree visualization.

DATASET:

•File: marketing_campaign.csv
•Separator: Tab (\t)
•Source: Kaggle - Marketing Campaign Dataset

LIBRARIES USED:

•PANDAS
•scikit-learn
•matplotlib
•seaborn

PROJECT WORKFLOW:

1. Upload and Load Data

Load the dataset using pandas with a tab separator.
Preview the first few rows.

2. Preprocessing

Drop irrelevant columns: ID, Dt_Customer
Remove missing values.
Encode categorical features using LabelEncoder.

3. Modeling

Define X (features) and y (target = Response).
Split into training and test sets using train_test_split.
Train a DecisionTreeClassifier with max_depth=4.

4. Evaluation

Predict on the test set.
Print model accuracy using accuracy_score.

5. Visualization

Use plot_tree() from sklearn with:
Proper figure size (30x20)
Rounded and color-filled nodes
Feature and class names
Print decision rules using export_text().

OUTPUT EXAMPLE:

•Model Accuracy: ~0.85 (varies with data split)
•Decision Tree: Fully visible with no overlapping
•Textual Rules: Printed in the output for interpretability

How To Run:

1.Open the notebook in Google Colab
2.Upload the marketing_campaign.csv file when prompted
3.Run all cells from top to bottom