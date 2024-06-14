# Car-Price-Prediction

### Problem Statement:
The dataset contains information about the used cars.
The main aim is to predict the selling price of these used cars using Machine Learning techniques.

### Project Lifecycle:
The following approach explains the project lifecycle.

• Data Preprocessing : Exploring the data using pandas, numpy & identifying null values, missing values and outliers present in the dataset

• Data Visualization : Visualize the data through matplotlib, seaborn for finding insights of the variables present the dataset.

• Feature Engineering : Cleaning the data to select and transform the most relevant variables from raw data.

• Model Building : For model building Random Forest Regressor algorithm is used to predict the target variable.

• Tuning : Performed Hyperparameter tuning using randomizedSearchCV.

• Deployment : The project is deployed using Flask on Heroku.

### Technologies Used:
• Jupyter Notebook is used for IDE. 

• For creating webapp Flask framework is used.

• Front End is developed using HTML, CSS.

• Heroku is used for Model Deployment.

## How to run?

### 1. Clone the Repository

```bash
git clone https://github.com/Vinit21592/ShadowFox-AIML-Internship.git
```

### 2. Navigate to the Project Directory and press "code ." this will open vscode editor

```bash
cd ShadowFox-AIML-Internship
```

### 3. Open terminal and navigate to Task2 folder

```bash
cd Task2
```

### 4. Create a new environment

```bash
conda create -p venv python=3.7 -y
```

### 5. Activate the environment

```bash
source activate venv/
```

### 6. Install the requirements package

```bash
pip install -r requirements.txt
```

### 7. Run your application

```bash
python app.py
```

### 8. After running above python script you will see this kind of app interface
![Car-Price-Prediction app screenshot](https://github.com/Vinit21592/ShadowFox-AIML-Internship/assets/78821357/88829783-1d51-4428-91a6-7a7a43c200ba)
