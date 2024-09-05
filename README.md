# Travel Package Price Predictor
![Banner](https://github.com/ANURUDRA-JENA/Travel-Hospitality-Analysis/blob/d398181ca2690a1f2b4e7fee45f17726feb64e90/Assets/Project%20Banner.png)



<h2>Overall Summary</h2>
<p>&gt; Improved model performance and accuracy by transforming the normalized and scaled data &nbsp; after encoding newly created features post feature selection and data processing.</p>
<p>&gt; Conducted PCA for dimensionality reduction and utilized NLP to embed text columns using a &nbsp; specific pre-trained MiniLM model and generated a single feature vector for further analysis.</p>
<p>&gt; Conducted Regression analysis using regression models like Decision Tree Regressor, Linear &nbsp; Regression and Random Forest Regressor and evaluated them with respective metrics.</p>
<p>&gt; Potentive &nbsp;approach &nbsp;on &nbsp;utilizing &nbsp;Flask &nbsp;to &nbsp;create &nbsp;RESTful &nbsp;APIs &nbsp;and &nbsp;provide real-time travel &nbsp; package price predictions with modularity and reusability in mind.</p>


<p style="text-align: left;color: rgb(210, 208, 206);background-color: rgb(43, 43, 43);font-size: 14px;"><strong><strong style="font-size: var(--cib-type-body1-stronger-font-size);">1. Learning Objective and Material</strong></strong>:</p>
<ul style="text-align: left;color: rgb(210, 208, 206);background-color: rgb(43, 43, 43);font-size: 14px;">
    <li><strong>Objective</strong>: Predict travel package prices using historical data and machine learning.</li>
    <li><strong>Material</strong>: Introduction to price prediction, impact on sales, and profitability.</li>
</ul>
<p style="text-align: left;color: rgb(210, 208, 206);background-color: rgb(43, 43, 43);font-size: 14px;"><strong><strong style="font-size: var(--cib-type-body1-stronger-font-size);">2. Basics of Regression Models</strong></strong>:</p>
<ul style="text-align: left;color: rgb(210, 208, 206);background-color: rgb(43, 43, 43);font-size: 14px;">
    <li><strong>Regression Models</strong>: Linear, multiple linear, polynomial, logistic, decision trees, and random forests.</li>
    <li><strong>Metrics</strong>: R-squared, MSE, RMSE.</li>
</ul>
<p style="text-align: left;color: rgb(210, 208, 206);background-color: rgb(43, 43, 43);font-size: 14px;"><strong><strong style="font-size: var(--cib-type-body1-stronger-font-size);">3. Feature Selection and Engineering</strong></strong>:</p>
<ul style="text-align: left;color: rgb(210, 208, 206);background-color: rgb(43, 43, 43);font-size: 14px;">
    <li><strong>Techniques</strong>: Correlation analysis, RFE, PCA, feature scaling, one-hot encoding, binning, text mining.</li>
    <li><strong>Importance</strong>: Reduces noise, improves performance, interpretability, and efficiency.</li>
</ul>
<p style="text-align: left;color: rgb(210, 208, 206);background-color: rgb(43, 43, 43);font-size: 14px;"><strong><strong style="font-size: var(--cib-type-body1-stronger-font-size);">4. Addressing Multicollinearity and Overfitting</strong></strong>:</p>
<ul style="text-align: left;color: rgb(210, 208, 206);background-color: rgb(43, 43, 43);font-size: 14px;">
    <li><strong>Multicollinearity</strong>: High correlation between features.</li>
    <li><strong>Overfitting</strong>: Model learns noise instead of patterns.</li>
    <li><strong>Techniques</strong>: Regularization, cross-validation, pruning.</li>
</ul>
<p style="text-align: left;color: rgb(210, 208, 206);background-color: rgb(43, 43, 43);font-size: 14px;"><strong><strong style="font-size: var(--cib-type-body1-stronger-font-size);">5. Practical Implementation</strong></strong>:</p>
<ul style="text-align: left;color: rgb(210, 208, 206);background-color: rgb(43, 43, 43);font-size: 14px;">
    <li><strong>Data Preprocessing</strong>: Handling missing values, dropping irrelevant columns.</li>
    <li><strong>Model Training</strong>: Linear regression and decision tree-based models.</li>
    <li><strong>Hyperparameter Tuning</strong>: Grid search for optimal parameters.</li>
    <li><strong>Evaluation</strong>: R-squared, MSE, RMSE.</li>
</ul>
<p style="text-align: left;color: rgb(210, 208, 206);background-color: rgb(43, 43, 43);font-size: 14px;"><strong><strong style="font-size: var(--cib-type-body1-stronger-font-size);">6. Results</strong></strong>:</p>
<ul style="text-align: left;color: rgb(210, 208, 206);background-color: rgb(43, 43, 43);font-size: 14px;">
    <li><strong>Linear Regression</strong>: R&sup2; of 1.00, MSE of 0.00, RMSE of 0.00.</li>
    <li><strong>Decision Tree-Based Model</strong>: R&sup2; of 0.72, MSE of 2255547.88, RMSE of 1501.85 after tuning.</li>
</ul>
<p style="text-align: left;color: rgb(210, 208, 206);background-color: rgb(43, 43, 43);font-size: 14px;">This project demonstrates the process of building a travel package price prediction model, from data preprocessing to model evaluation and tuning.</p>

<h3>The Flask App</h3>

![flaskapp](https://github.com/ANURUDRA-JENA/Travel-Hospitality-Analysis/blob/d398181ca2690a1f2b4e7fee45f17726feb64e90/Assets/TPPP.png)
