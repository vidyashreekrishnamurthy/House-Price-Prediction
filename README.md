                                                   🏠 House Price Prediction


A simple web app that predicts house prices using a machine learning model trained on housing data. 
The app is powered by Flask or the backend and a Random Forest Regressor from scikit-learn for the predictive model.




📊 Features Used
* OverallQual: Overall material and finish quality
* GrLivArea: Above grade (ground) living area square feet
* GarageCars: Size of garage in car capacity
* TotalBsmtSF: Total square feet of basement area
  



⚙️ How It Works
1. Model Training (train_model.py):
    * Loads and preprocesses the train.csv dataset.
    * Trains a RandomForestRegressor model.
    * Saves the trained model as house_price_model.pkl.

2. Web Application (app.py):

    * Loads the trained model.
    * Accepts input from users through a form.
    * Returns the predicted house price.
      



🚀 How to Run
1. Install Requirements
pip install -r requirements.txt

2. Train the Model (Optional - already trained)
python train_model.py

3. Run the Web App
python app.py

4. Open in Browser
Go to http://127.0.0.1:5000/




🧪 Sample Input (via form)
* Overall Quality: 7
* Living Area (sq ft): 2000
* Garage Cars: 2
* Basement Area (sq ft): 1000




🧠 Model
* Algorithm: Random Forest Regressor
* Library: scikit-learn
* Evaluation Metric: Mean Squared Error (MSE)




📦 Requirements
From requirements.txt:
* Flask
* NumPy
* Pandas
* scikit-learn
* joblib




👤 Author – @https://github.com/vidyashreekrishnamurthy



Screenshots:


1.
  <img width="953" height="494" alt="image" src="https://github.com/user-attachments/assets/6fd762ea-6ee0-4bcf-a371-7067139c5b02" />


2.
 <img width="948" height="182" alt="image" src="https://github.com/user-attachments/assets/c749e0d3-d881-426d-81ce-1eed1dcf3c99" />

3.
 <img width="949" height="482" alt="image" src="https://github.com/user-attachments/assets/729893f5-d60a-4b7d-968c-11eb6438e0cf" />


4.
 <img width="917" height="469" alt="image" src="https://github.com/user-attachments/assets/7f93c289-089d-4a2e-8173-a59387dab116" />

5.
 <img width="920" height="475" alt="image" src="https://github.com/user-attachments/assets/8e93b93b-ba41-477a-af03-aecfa5ade2e8" />













