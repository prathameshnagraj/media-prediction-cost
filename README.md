<h1 align="center">📊 Media Prediction and Its Cost</h1>
<h3 align="center">🎯 Predicting Customer Acquisition Cost (CAC) with Machine Learning</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Project-Type%3A%20Academic-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/License-MIT-lightgrey?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Model-Built%20with%20Scikit--Learn-blue?style=for-the-badge&logo=scikit-learn" />
</p>

<hr>

<h2>📌 Overview</h2>

<p>
This project was developed as part of the <strong>Applied Machine Learning</strong> course at UT Dallas. 
Our goal was to help a fictional retail chain, <b>Food Mart USA</b>, improve their marketing budget by predicting the <strong>Customer Acquisition Cost (CAC)</strong> across various campaigns and store types.
</p>

<p>
Using a dataset of 60,000 customers sourced from Kaggle, we built regression models to identify cost drivers and recommend optimizations for ROI-focused marketing.
</p>

<hr>

<h2>🧠 Problem Statement</h2>

<p>
Predicting <strong>Customer Acquisition Cost (CAC)</strong> helps businesses allocate their marketing budget efficiently.
We used media campaign data, store attributes, and customer demographics to forecast CAC and optimize resource allocation across Food Mart's marketing channels.
</p>

<hr>

<h2>🔍 Dataset</h2>

<ul>
  <li>📁 <code>media prediction and its cost.csv</code> from Kaggle</li>
  <li>👥 60,000 customers</li>
  <li>🔢 Variables include: income, promotion type, store size, product preferences, and media exposure</li>
</ul>

<hr>

<h2>🧪 ML Approach</h2>

<ul>
  <li>📊 <strong>EDA</strong>: Data cleaning, visualization, and statistical testing</li>
  <li>🧹 <strong>Preprocessing</strong>: One-hot encoding, correlation filtering, feature reduction</li>
  <li>📈 <strong>Models Used</strong>:
    <ul>
      <li>Linear Regression</li>
      <li>Polynomial Regression with Lasso</li>
      <li>Decision Tree Regressor</li>
      <li><strong>Random Forest Regressor (Best Performer)</strong></li>
    </ul>
  </li>
</ul>

<hr>

<h2>📊 Model Evaluation Results</h2>

<table>
  <thead>
    <tr>
      <th>Model</th>
      <th>R²</th>
      <th>MAE</th>
      <th>RMSE</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Linear Regression</td>
      <td>0.37</td>
      <td>19.62</td>
      <td>23.95</td>
    </tr>
    <tr>
      <td>Polynomial Regression (Lasso)</td>
      <td>0.99</td>
      <td>1.88</td>
      <td>3.25</td>
    </tr>
    <tr>
      <td>Decision Tree Regressor</td>
      <td>0.997</td>
      <td>0.08</td>
      <td>1.69</td>
    </tr>
    <tr>
      <td><strong>Random Forest Regressor</strong></td>
      <td><strong>0.998</strong></td>
      <td><strong>0.08</strong></td>
      <td><strong>1.13</strong></td>
    </tr>
  </tbody>
</table>

<p><em>🎉 Final model (Random Forest) achieved R² = 0.998 and MAE ≈ $0.08 — extremely high predictive power!</em></p>

<hr>

<h2>📁 Folder Structure</h2>

<pre>
media-prediction-cost/
├── AML_Project_Final.ipynb
├── media prediction and its cost.csv
├── Report - Group 7.pdf
├── requirements.txt
├── LICENSE
├── README.md
└── assets/
    └── (charts, demo visuals)
</pre>

<hr>

<h2>🙋‍♂️ Author</h2>

<p>
<strong>Prathamesh Nagraj</strong><br>
📧 <a href="mailto:ppnagraj.work@gmail.com">ppnagraj.work@gmail.com</a><br>
🔗 <a href="https://www.linkedin.com/in/prathamesh-nagraj/">LinkedIn Profile</a>
</p>

<hr>

<h2>📄 License</h2>

This project is licensed under the <strong>MIT License</strong> — feel free to use, fork, or adapt it.

<hr>

<p align="center"><em>“Let the data drive the dollars.”</em></p>
