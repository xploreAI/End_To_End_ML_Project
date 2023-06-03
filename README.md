# Student Exam Performance Indicator

This project is a student exam performance indicator web application. It predicts the math scores of students based on various factors such as gender, race or ethnicity, parental level of education, lunch type, test preparation course, and reading and writing scores.

## Project Structure

The project structure is organized as follows:

.
├── app.py
├── setup.py
├── src/
│ ├── pipeline/
│ │ └── predict_pipeline.py
│ ├── exception.py
│ ├── logger.py
│ └── utils.py
├── templates/
│ ├── index.html
│ └── home.html
├── notebook/
│ ├── catboost_info/
│ ├── data/
│ │ ├── stud.csv
│ ├── EDA student performance.ipynb
│ └── Model Training.ipynb
└── artifacts/
├── data.csv
├── model.pkl
├── preprocessor.pkl
├── test.csv
└── train.csv


- app.py: Main Flask application file containing the routes and logic.
- setup.py: Python package setup file for the project.
- src/: Directory containing the project source code.
  - pipeline/: Directory containing the prediction pipeline code.
    - predict_pipeline.py: Module for loading the trained model and performing predictions.
  - exception.py: Module defining custom exception classes.
  - logger.py: Module defining the logging configuration.
  - utils.py: Module containing utility functions.
- templates/: Directory containing HTML templates for the web application.
  - index.html: Home page template.
  - home.html: Form template for entering student details and displaying predictions.
- notebook/: Directory containing Jupyter notebooks and related files.
  - catboost_info/: Directory containing CatBoost model information.
  - data/: Directory containing data files used for exploration, training, and predictions.
    - stud.csv: Dataset file containing student performance data.
  - EDA student performance.ipynb: Jupyter notebook for exploratory data analysis.
  - Model Training.ipynb: Jupyter notebook for model training.
- artifacts/: Directory containing additional project artifacts.
  - data.csv: Additional data file.
  - model.pkl: Serialized trained model file.
  - preprocessor.pkl: Serialized data preprocessor file.
  - test.csv: Test dataset file.
  - train.csv: Training dataset file.

## Installation

To run the web application locally, follow these steps:

1. Clone the repository:

   `git clone https://github.com/your-username/student-performance-indicator.git`

2. Navigate to the project directory:

   `cd student-performance-indicator`

3. Create a virtual environment:

   `python -m venv env`

4. Activate the virtual environment:

   `source env/bin/activate`  (For Linux/Mac)

   `env\Scripts\activate`  (For Windows)

5. Install the required dependencies:

   `pip install -r requirements.txt`

6. Start the application:

   `python app.py`

7. Open your web browser and visit http://localhost:5000 to access the application.

## Usage

1. Open the web application in your browser.

2. Enter the student details and click on the "Predict" button.

3. The predicted math score for the student will be displayed.

## License

This project is licensed under the [MIT License](LICENSE).


## Installation

To run the web application locally, follow these steps:

1. Clone the repository:

   git clone https://github.com/your-username/student-performance-indicator.git

2. Navigate to the project directory:

   cd student-performance-indicator

3. Create a virtual environment:

   python -m venv env

4. Activate the virtual environment:

   source env/bin/activate  # For Linux/Mac
   env\Scripts\activate  # For Windows

5. Install the required dependencies:

   pip install -r requirements.txt

6. Start the application:

   python app.py

7. Open your web browser and visit http://localhost:5000 to access the application.

## Usage

1. Open the web application in your browser.
2. Fill in the student details, including gender, race or ethnicity, parental level of education, lunch type, test preparation course, reading score, and writing score.
3. Click on the "Predict your Maths Score" button.
4. The application will display the predicted math score based on the provided student details.
5. You can enter new details and predict again.

Enjoy using the Student Exam Performance Indicator!
