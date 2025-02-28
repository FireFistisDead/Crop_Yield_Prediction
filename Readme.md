🌾 _**Crop Yield Prediction using Polynomial Regression**_

📌 _Project Overview_

This project aims to predict crop yield (quintal per hectare) for different states in India based on cultivation costs. Using Polynomial Regression, we have developed a highly accurate model to estimate crop yields.

📊 Dataset

The dataset consists of:

State: The region where the crop is grown.

Cost of Cultivation (C2) (₹/Hectare): The total cost incurred for cultivation.

Yield (Quintal/Hectare): The output quantity per hectare.

After preprocessing, we use Cost of Cultivation (C2) as the primary independent variable for yield prediction.

🛠️ Tech Stack

Python

Scikit-learn

Pandas & NumPy

Matplotlib & Seaborn (for visualization)

🚀 Project Workflow

_Data Preprocessing:_

1.) Handled missing values.

2.) Dropped unnecessary columns ('Crop', 'Cost of Cultivation A2+FL').

3.) Encoded categorical data (if needed).

4.) Feature Selection & Engineering:

5.) Analyzed feature correlation.

6.) Selected Cost of Cultivation (C2) as the main predictor.

_Model Training:_

-> Applied Polynomial Regression (degree=2) for non-linear patterns.

-> Split data (80% training, 20% testing).

📈 _Model Performance:-_

**Mean Squared Error (MSE):-3,817.58**

**R-squared Score (R²):-** **0.9577 (95.77%)**

📊 _Visualizations_
-> State-wise Prediction Graph (Comparing actual vs. predicted yield).

-> Heatmap (Showing feature correlation).

-> Scatter Plot (Analyzing model fit).

🔮 _Future Enhancements_

🔹 Deploy the Model: Use Flask/Streamlit for real-time predictions.

🔹 Optimize with Degree 3 Polynomial Regression for possible accuracy improvements.

🔹 Try Lasso/Ridge Regression to prevent overfitting.

🔹 Save the Model for Reuse: joblib.dump(model, "yield_model.pkl").

🔹 Publish on Kaggle/GitHub to showcase the project.

📜 _License_
This project is licensed under the MIT License.

