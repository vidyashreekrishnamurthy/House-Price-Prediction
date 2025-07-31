🏠 House Price Prediction


A simple web app that predicts house prices using a machine learning model trained on housing data. 
The app is powered by Flask or the backend and a Random Forest Regressor from scikit-learn for the predictive model.




📂 Project Structure
├── app.py                  # Flask application to serve predictions
├── train_model.py          # Script to train and save the model
├── house_price_model.pkl   # Trained model file
├── train.csv               # Dataset used to train the model
├── requirements.txt        # Python dependencies
├── templates/
│   └── index.html          # HTML form for input 
|---Static/
    |___ houses_prices.jpg




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


<img width="953" height="494" alt="image" src="https://github.com/user-attachments/assets/6fd762ea-6ee0-4bcf-a371-7067139c5b02" />





