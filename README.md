# CO2-Emission-Prediction
projrct link (https://co2-emission-prediction-yb6wny7efuoevwbb8qzp3w.streamlit.app/)


# Description of The Project:

<h3><b>Business Objective of the project</b></h3>

- The primary objective of the project is to develop a model that can accurately predict CO2 emissions based on different engine features of cars. 
- The goal is to estimate the amount of CO2 a car will emit using the provided data.

# Description of The Data:

- The data used in the project was collected from the Canadian Government's Official [Website](https://open.canada.ca/data/en/dataset/98f1a129-f628-4ce4-b24d-6f16bf24dd64#wb-auto-6).

## About Data 📈 

### It includes the following attributes:

- <b>Make:</b> Car brand under study.
- <b>Model:</b> Specific model of the car.
- <b>Vehicle_class:</b> Car body type.
- <b>Engine_size:</b> Size of the car engine in liters.
- <b>Cylinders:</b> Number of cylinders.
- <b>Transmission:</b> Type of transmission (e.g., automatic, manual).
- <b>Fuel_type:</b> Type of fuel used by the car.
- <b>Fuel_consumption_city:</b> City fuel consumption ratings in liters per 100 kilometers.
- <b>Fuel_consumption_hwy:</b> Highway fuel consumption ratings in liters per 100 kilometers.
- <b>Fuel_consumption_comb(l/100km):</b> Combined fuel consumption rating (city and highway) in L/100 km.
- <b>Fuel_consumption_comb(mpg):</b> Combined fuel consumption rating in miles per gallon (mpg).
- <b>Co2_emissions:</b> Tailpipe emissions of carbon dioxide for combined city and highway driving, in grams per kilometer.


# Tools and Technologies:

#### The project was developed using various tools and technologies, including:
- Python programming language
- Libraries such as NumPy, Matplotlib, SciPy, scikit-learn, and Streamlit
- Linear Regression, Random Forest, K-Nearest Neighbors (KNN), and Support Vector Regression (SVR) models for prediction
- Deployment on the cloud using Streamlit


## How to install these libraries?
### You can install these libraries by using the command.

- You can install all the libraries in your system which I have used in my project by using only one command. 
- You will need Python in your system to use this command. You can use this given link to install Python in your system : [Python](https://www.python.org/downloads/)
- After installation of Python, you need to run this command in your command prompt.

```bash
pip install -r requirements.txt 
```
# Model Building:

- The project involved building and evaluating several machine learning models, including Linear Regression, Random Forest, KNN, and SVR.
- The Random Forest model yielded the highest accuracy among these models and was selected for deployment.


# Deployment:

- The project was deployed using Streamlit, allowing users to interact with the model and make predictions on CO2 emissions based on car engine features.
- The deployment version of the project can be accessed through a provided link :[Project](https://co2-emission-prediction-yb6wny7efuoevwbb8qzp3w.streamlit.app/)

# Running the Project:

- To run the project locally, one can install the required libraries using the provided command in the command prompt. Use the below Streamlit command to launch the application.
```bash
streamlit run app.py 
```

### The project not only demonstrates technical skills but also contributes to environmental awareness and sustainable practices. It effectively combines data analysis, machine learning, and software development to address real-world challenges.

---
<p align="center">
<b>Enjoy Coding</b>❤
</p>

