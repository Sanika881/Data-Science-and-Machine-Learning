<h2>Used Car Price Prediction</h2>
📌 Overview This project is all about diving into the world of used car prices and predicting them using machine learning techniques. I’ve got a dataset that includes important details like the car's brand, model, mileage, engine capacity, and selling price. The aim is to uncover trends in the used car market, tidy up the data, and create some predictive models.

<br>📂 Dataset The dataset features some key elements:

car_name – The name of the car

brand – The manufacturer behind the car

model – The specific model of the car

vehicle_age – How old the car is (in years)

km_driven – The total distance the car has traveled

seller_type – The type of seller (Dealer or Individual)

fuel_type – The kind of fuel the car uses (Petrol, Diesel, or CNG)

transmission_type – The type of transmission (Manual or Automatic)

mileage – The car's mileage (in km/l)

engine – The engine capacity (in cc)

max_power – The maximum power output of the car

selling_price – The price at which the car is sold (this is our target variable)


<br>🔍 Data Preprocessing Checking for Duplicates – We identified and removed any duplicate entries.

Handling Missing Values – We filled in missing mileage values using the mean.

Detecting Outliers – We used boxplots to take a closer look at price distribution.

Scaling & Normalization – We applied standardization with StandardScaler().

Encoding Categorical Variables – We converted categorical features into numerical formats.


<br>📊 Exploratory Data Analysis (EDA) Histogram: Shows the distribution of car prices.

Scatter Plot: Illustrates the relationship between mileage and selling price.

Bar Chart: Compares average prices by brand.

Heatmap: Displays the correlation between numerical features.


<br>🤖 Machine Learning Models Linear Regression – Used for predicting car prices based on numerical features.

Decision Tree Regressor – Helps capture non-linear relationships.

Random Forest Regressor – Enhances prediction accuracy through ensemble learning.

Neural Network Model – Developed with TensorFlow for deep learning-based price predictions.


<br>🏆 Model Evaluation R² Score – This measures how well our regression models fit the data.

Accuracy Score – Evaluates the performance of our


<br>💡 Insights & Findings
The age of a vehicle and its mileage play a big role in determining its price.

Cars listed by dealers tend to be priced higher than those sold by individual sellers.

Luxury brands, such as BMW and Mercedes, usually command higher selling prices.

When it comes to resale value, diesel cars often outperform petrol cars.


<br>🛠️ Technologies Used

Python

Pandas & NumPy for data manipulation

Matplotlib & Seaborn for data visualization

Scikit-learn for machine learning models

TensorFlow/Keras for deep learning models


 
