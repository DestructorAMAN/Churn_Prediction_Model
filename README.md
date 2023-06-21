<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
</head>
<body>
  <h1>Churn Prediction using Logistic Regression</h1>
  <p>This repository contains a project on churn prediction using logistic regression. Churn prediction is an important task in business analytics and customer retention strategies. The goal of this project is to develop a predictive model that can identify customers who are likely to churn, allowing companies to take proactive measures to retain those customers.</p>
  <h2>Dataset</h2>
  <p>The dataset used in this project is not included in the repository. However, the code is designed to work with any similar churn dataset that contains relevant features for prediction. The dataset should be in CSV format, with each row representing a customer and each column representing a feature or attribute.</p>
  <h2>Dependencies</h2>
  <p>The following dependencies are required to run the code:</p>
  <ul>
    <li>Python 3.6+</li>
    <li>NumPy</li>
    <li>Pandas</li>
    <li>Scikit-learn</li>
  </ul>
  <p>You can install the dependencies by running the following command:</p>
  <pre><code>pip install -r requirements.txt</code></pre>
  <h2>Usage</h2>
  <ol>
    <li>Clone the repository:</li>
    <pre><code>git clone https://github.com/your-username/churn-prediction.git</code></pre>
    <li>Navigate to the project directory:</li>
<pre><code>cd churn-prediction</code></pre>

<li>Place your dataset file (in CSV format) in the project directory.</li>

<li>Modify the <code>config.py</code> file to specify the filename of your dataset and other configuration parameters.</li>

<li>Run the <code>main.py</code> file:</li>
<pre><code>python main.py</code></pre>
  </ol>
  <p>The code will read the dataset, preprocess the data, train the logistic regression model, and evaluate its performance. The results will be displayed in the console.</p>
  <h2>Customization</h2>
  <p>You can customize various aspects of the project by modifying the <code>config.py</code> file. Here are some parameters you can adjust:</p>
  <ul>
    <li><code>dataset_filename</code>: The filename of your dataset.</li>
    <li><code>target_column</code>: The column name or index of the target variable (churn).</li>
    <li><code>feature_columns</code>: A list of column names or indices representing the feature variables.</li>
    <li><code>test_size</code>: The proportion of the dataset to be used as the test set.</li>
    <li><code>random_state</code>: The random seed for reproducibility.</li>
    <li><code>C</code>: The inverse of regularization strength for logistic regression.</li>
  </ul>
  <p>Feel free to experiment with different configurations to achieve better prediction results.</p>
  <h2>Results</h2>
  <p>The results of the churn prediction model will be displayed in the console. The evaluation metrics include accuracy, precision, recall, and F1-score. Additionally, a confusion matrix will be shown to visualize the performance of the model in predicting churned and non-churned customers
