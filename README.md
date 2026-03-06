<h1>✈️ Flight Delay Prediction using Machine Learning</h1>

<p>
This project develops a <strong>machine learning model to predict flight delays</strong> based on operational and flight-related features.
The goal is to anticipate potential delays and support <strong>airport operational planning and decision-making</strong>.
</p>

<p>
By integrating predictive models into airport operations, it is possible to improve <strong>efficiency</strong>, reduce <strong>costs</strong>, and optimize <strong>resource allocation</strong>.
</p>

<hr>

<h2>📊 Project Overview</h2>

<p>
Flight delays are a common challenge in airport operations. Predicting them in advance allows airports and airlines to better plan their activities and mitigate operational disruptions.
</p>

<p>
In this project, we built a regression model capable of predicting the <strong>expected delay (in minutes)</strong> of a flight using features such as:
</p>

<ul>
  <li>flight arrival time</li>
  <li>airline</li>
  <li>aircraft type</li>
  <li>holiday indicator</li>
  <li>weekend indicator</li>
  <li>Schengen/non-Schengen flights</li>
</ul>

<p>
The model was trained and evaluated using <strong>Random Forest Regressor</strong> and validated with cross-validation techniques.
</p>

<hr>

<h2>🧠 Machine Learning Workflow</h2>

<ol>
  <li><strong>Exploratory Data Analysis (EDA)</strong><br>
      Understanding the dataset, identifying distributions, and visualizing patterns in delays.
  </li>
  <li><strong>Feature Engineering</strong><br>
      Creation of additional features such as weekend indicators, holiday indicators, and categorical encoding using one-hot encoding.
  </li>
  <li><strong>Baseline Model</strong><br>
      A <code>DummyRegressor</code> was used as a baseline to compare model performance.
  </li>
  <li><strong>Model Training</strong><br>
      A <strong>RandomForestRegressor</strong> was trained to capture non-linear relationships in the data.
  </li>
  <li><strong>Model Evaluation</strong><br>
      The model was evaluated using:
      <ul>
        <li>RMSE (Root Mean Squared Error)</li>
        <li>MAE (Mean Absolute Error)</li>
        <li>R² Score</li>
      </ul>
  </li>
  <li><strong>Cross-Validation</strong><br>
      K-Fold cross-validation was used to ensure model stability and avoid overfitting.
  </li>
  <li><strong>Hyperparameter Tuning</strong><br>
      <code>GridSearchCV</code> was applied to find the best model configuration.
  </li>
  <li><strong>Feature Importance Analysis</strong><br>
      Feature importance was analyzed to understand which variables have the strongest impact on delay prediction.
  </li>
  <li><strong>Model Saving and Loading</strong><br>
      The final trained model was saved using <code>pickle</code> and later loaded to perform predictions on new data.
  </li>
</ol>

<hr>

<hr>

<h2>🛠️ Technologies Used</h2>

<ul>
  <li>Python</li>
  <li>Pandas</li>
  <li>NumPy</li>
  <li>Matplotlib</li>
  <li>Seaborn</li>
  <li>Scikit-Learn</li>
  <li>Yellowbrick</li>
</ul>

<h2>🤖 Machine Learning Models</h2>

<ul>
  <li>DummyRegressor (baseline model)</li>
  <li>Random Forest Regressor</li>
  <li>GridSearchCV (hyperparameter tuning)</li>
  <li>K-Fold Cross Validation</li>
</ul>

<hr>

<h2>📂 Repository Structure</h2>

<pre>
flight-delay-prediction
│
├── flight-delay-ml-model.ipynb
├── model_prod.pkl
├── flights.csv
└── README.md
</pre>

<hr>

<h2>🚀 Future Improvements</h2>

<ul>
  <li>exploring additional machine learning models</li>
  <li>improving feature engineering techniques</li>
  <li>performing predictions using the trained model</li>
  <li>model persistence and inference using pickle</li>
</ul>

<hr>

<h2>👩‍💻 Author</h2>

<p>
<strong>Adriely Lopes</strong><br>
Data professional specializing in Machine Learning and predictive analytics, applying data-driven approaches to solve real-world problems.
</p>
