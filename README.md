### Medical Insurance Cost Prediction

This project aims to predict the medical insurance cost for individuals based on several factors such as age, BMI (Body Mass Index), number of children, smoking habits, and region. The prediction model is built using machine learning techniques, specifically regression algorithms, to provide accurate estimates of medical insurance costs.

#### Dataset
The dataset used for this project contains information about individuals, including their age, sex, BMI, number of children, smoking status, region, and medical insurance costs. The dataset was obtained from [source].

#### Methodology
1. **Data Collection**: The dataset was collected from [source].
2. **Data Preprocessing**: The dataset underwent preprocessing steps such as handling missing values, encoding categorical variables, and scaling numerical features.
3. **Exploratory Data Analysis (EDA)**: Exploratory data analysis was performed to gain insights into the relationships between different variables and their impact on medical insurance costs.
4. **Feature Engineering**: Feature engineering techniques were applied to extract useful information from the existing features and create new features if necessary.
5. **Model Selection and Training**: Several regression algorithms were evaluated, including Linear Regression, Ridge Regression, Lasso Regression, and Gradient Boosting Regression. Hyperparameter tuning was performed to optimize the models.
6. **Model Evaluation**: The models were evaluated using performance metrics such as Mean Squared Error (MSE), Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R-squared (R2) score.
7. **Model Deployment**: The best-performing model was deployed using a Flask web application. Users can input their information, and the model predicts their medical insurance cost.

#### Repository Structure
- **data/**: Contains the dataset used for training the model.
- **models/**: Stores the trained machine learning models.
- **notebooks/**: Jupyter notebooks used for data exploration, preprocessing, and model training.
- **app.py**: Flask application for model deployment.
- **templates/**: HTML templates for the web application.
- **static/**: Contains CSS stylesheets and images for the web application.

#### Usage
1. Clone the repository: `git clone <repository-url>`
2. Install the required dependencies: `pip install -r requirements.txt`
3. Run the Flask application: `python server.py`
4. Access the web application in your browser at `http://localhost:5000`
